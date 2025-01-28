
# Solución: Práctica 02 - Instalación del Laboratorio con KVM/QEMU

## Paso 1: Instalación de paquetes necesarios
Instala los paquetes requeridos para KVM/QEMU:
```
sudo apt update
sudo apt install qemu-kvm libvirt-daemon-system libvirt-clients bridge-utils virt-manager
```
**Explicación:** Esto asegura que el sistema tenga todo lo necesario para crear y gestionar máquinas virtuales.

---

## Paso 2: Verificación del soporte de virtualización
Verifica si tu CPU soporta virtualización:
```
egrep -c '(vmx|svm)' /proc/cpuinfo
```
**Explicación:** Si el resultado es mayor a 0, tu CPU soporta virtualización.

---

## Paso 3: Configuración de red
Crea un bridge de red para que las VMs accedan a la red externa:
1. Edita el archivo de configuración de red (ejemplo en Ubuntu 20.04):
```
sudo nano /etc/netplan/01-netcfg.yaml
```
2. Configura el bridge con el siguiente ejemplo:
```yaml
network:
  version: 2
  renderer: networkd
  ethernets:
    enp0s3:
      dhcp4: no
  bridges:
    br0:
      interfaces: [enp0s3]
      dhcp4: yes
```
3. Aplica la configuración:
```
sudo netplan apply
```

---

## Paso 4: Creación de una máquina virtual
1. Crea una imagen de disco para la VM:
```
qemu-img create -f qcow2 /var/lib/libvirt/images/mi_vm.qcow2 20G
```
2. Inicia el asistente de creación de VMs con `virt-manager` o usa el comando:
```
virt-install --name mi_vm --ram 2048 --vcpus 2 --disk path=/var/lib/libvirt/images/mi_vm.qcow2,format=qcow2 --os-type linux --os-variant ubuntu20.04 --network bridge=br0 --graphics spice --cdrom /path/to/ubuntu.iso
```

**Explicación:** Este comando configura una VM con 2 GB de RAM, 2 CPUs, y un puente de red.

---

## Paso 5: Prueba del laboratorio
Asegúrate de que la VM se haya creado correctamente y pueda acceder a la red externa. Verifica su conectividad con un `ping`:
```
ping google.com
```
