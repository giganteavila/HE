Para los siguientes ejercicios prácticos, Luis necesitará montar un laboratorio con una máquina de ataque y una máquina víctima, ambas ejecutándose sobre KVM/QEMU. A continuación, se detallan las características y el procedimiento a seguir:

- **Herramienta de virtualización:** Utilizar **KVM/QEMU** (con libvirt y virt-manager para mayor facilidad de uso).

- **Configuración de red:**  

  - Crear y configurar una red NAT interna con el direccionamiento **10.0.2.0/24**.  
  - Esta red NAT permitirá que todas las máquinas virtuales conectadas a ella estén en el mismo segmento de red, pudiendo comunicarse entre sí.

- **Máquina de ataque (Kali Linux):**  

  - Descargar la imagen de Kali Linux desde el enlace correspondiente (no incluido en el texto original).
  - Instalar la máquina virtual en KVM/QEMU y conectarla a la red NAT.

- **Máquina víctima (Metasploitable2):**  

  - Descargar la imagen de Metasploitable2 (en formato VMDK habitualmente).  

  - Realizar una conversión de la imagen para que sea compatible con KVM/QEMU. Por ejemplo, utilizando la herramienta `qemu-img`:

    ```bash
    qemu-img convert -f vmdk -O qcow2 Metasploitable.vmdk Metasploitable.qcow2
    ```

  - Una vez convertida, crear la máquina virtual en KVM/QEMU y conectarla a la misma red NAT.

## Pasos Detallados

### 1. Instalación de KVM/QEMU y virt-manager (en Linux)

- En sistemas basados en Debian/Ubuntu:

  ```bash
  sudo apt update
  sudo apt install qemu-kvm libvirt-daemon libvirt-daemon-system libvirt-clients bridge-utils virt-manager
  sudo systemctl enable libvirtd
  sudo systemctl start libvirtd
  ```

- Asegurarse de que el usuario está en el grupo `libvirt`:

  ```bash
  sudo usermod -aG libvirt $USER
  ```

- Cerrar sesión y volver a iniciarla para que los cambios surtan efecto.

### 2. Creación de la Red NAT (10.0.2.0/24)

- Abrir `virt-manager` (interfaz gráfica) o utilizar `virsh`.  

- Mediante `virt-manager`:

  - Ir a *Editar* > *Detalles de la conexión* > *Redes virtuales*.
  - Crear una nueva red virtual.
  - Asignarle el rango `10.0.2.0/24`, habilitar DHCP si se desea, y asegurarse de que el modo de la red sea NAT.
  - Iniciar la red y dejarla activa al inicio del sistema.

- Alternativamente, con `virsh` (línea de comandos), crear un archivo XML con la definición de la red (por ejemplo `red-nat.xml`):

  ```xml
  <network>
    <name>red-nat</name>
    <forward mode='nat'/>
    <ip address='10.0.2.1' netmask='255.255.255.0'>
      <dhcp>
        <range start='10.0.2.2' end='10.0.2.254'/>
      </dhcp>
    </ip>
  </network>
  ```

  Luego importar y arrancar la red:

  ```bash
  virsh net-define red-nat.xml
  virsh net-start red-nat
  virsh net-autostart red-nat
  ```

### 3. Creación de la Máquina Virtual Kali Linux

- Descargar la imagen ISO de Kali Linux.  
- Abrir `virt-manager`.  
- Hacer clic en *Crear nueva máquina virtual*.  
- Seleccionar la ISO de Kali Linux.  
- Asignar recursos (CPU, RAM y Disco según las recomendaciones de Kali).  
- En la configuración de red, elegir la red virtual `red-nat` creada previamente.  
- Completar la instalación de Kali Linux siguiendo el asistente.

### 4. Creación de la Máquina Virtual Metasploitable2

- Descargar la imagen de Metasploitable2 (generalmente en formato VMDK).  

- Convertir la imagen a `qcow2` con `qemu-img`:

  ```bash
  qemu-img convert -f vmdk -O qcow2 Metasploitable.vmdk Metasploitable.qcow2
  ```

- En `virt-manager`, crear una nueva máquina virtual:  

  - Seleccionar "Importar imagen de disco existente".  
  - Escoger el archivo `Metasploitable.qcow2`.  
  - Asignar recursos mínimos (Metasploitable2 no requiere muchos).  
  - En la configuración de red, seleccionar la misma `red-nat`.  

- Finalizar la configuración e iniciar la máquina.

Con estos pasos, Luis dispondrá de una máquina de ataque (Kali Linux) y una máquina víctima (Metasploitable2) dentro de la misma red NAT (`10.0.2.0/24`) en un entorno KVM/QEMU, listo para realizar las pruebas de los ejercicios prácticos.
