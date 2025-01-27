# HE
Tema: Infraestructura como código (IaC): Ansible y Vagrant
1. Introducción a Infraestructura como Código (IaC)

1.1. ¿Qué es Infraestructura como Código?

    Definición y objetivos.
    Ventajas: automatización, reproducibilidad, escalabilidad, documentación y consistencia.
    Comparativa entre la gestión manual y IaC.

1.2. Herramientas populares de IaC:

    Terraform, Puppet, Chef, Ansible y Vagrant.
    Comparativa general: ventajas de cada herramienta.

2. Vagrant: Virtualización ligera para entornos de desarrollo

2.1. Introducción a Vagrant:

    ¿Qué es Vagrant?
    Arquitectura y componentes principales (Vagrantfile, proveedores, cajas).

2.2. Instalación y configuración de Vagrant:

    Instalación en sistemas Linux (ArcoLinux o Kubuntu como ejemplo).
    Proveedores comunes: VirtualBox, KVM/QEMU.

2.3. Uso básico de Vagrant:

    Creación de un archivo Vagrantfile.
    Comandos básicos: vagrant init, vagrant up, vagrant ssh, vagrant halt, vagrant destroy.

2.4. Gestión avanzada con Vagrant:

    Configuración de redes y sincronización de carpetas.
    Creación de entornos multi-máquina.
    Provisionamiento con shell scripts y Ansible desde Vagrant.

2.5. Integración de Vagrant con Ansible:

    Uso de Ansible como herramienta de provisionamiento en Vagrant.

3. Ansible: Automatización de la configuración

3.1. Introducción a Ansible:

    ¿Qué es Ansible?
    Comparativa con otras herramientas como Puppet y Chef.
    Principales componentes: Inventarios, módulos, playbooks y roles.

3.2. Instalación y configuración de Ansible:

    Instalación en Linux.
    Configuración básica del inventario.

3.3. Comandos básicos de Ansible:

    ansible, ansible-playbook, ansible-vault.
    Ejecución de tareas en sistemas remotos.

3.4. Playbooks de Ansible:

    Estructura de un playbook.
    Creación de tareas (tasks).
    Uso de módulos populares (apt, yum, copy, template, service).
    Variables y facts.

3.5. Roles en Ansible:

    Organización de tareas complejas.
    Uso de Galaxy para importar roles.

4. Integración de Vagrant y Ansible

4.1. Caso práctico:

    Configuración de un entorno multi-máquina con Vagrant.
    Provisionamiento automático con Ansible: instalación de servicios como Apache, MySQL, etc.

4.2. Ejercicio práctico:

    Configuración de una infraestructura que incluya:
        Una máquina con un servidor web.
        Otra máquina con una base de datos.
        Provisionamiento completo con Ansible.

5. Buenas prácticas en IaC

5.1. Organización del código:

    Estructura modular.
    Uso de variables y roles.

5.2. Control de versiones:

    Uso de Git para gestionar archivos de configuración.

5.3. Seguridad en IaC:

    Uso de ansible-vault para datos sensibles.
    Principios de idempotencia.

6. Evaluación

6.1. Ejercicios teóricos:

    Preguntas sobre conceptos de IaC, Vagrant y Ansible.

6.2. Ejercicios prácticos:

    Configurar un entorno básico con Vagrant.
    Crear un playbook de Ansible para configurar servicios en máquinas virtuales.

6.3. Proyecto final:

    Diseñar y desplegar una infraestructura completa que incluya:
        Al menos dos máquinas virtuales gestionadas con Vagrant.
        Provisionamiento con Ansible para instalar y configurar servicios.

Recursos adicionales

    Documentación oficial de Vagrant
    Documentación oficial de Ansible
    Ejemplos prácticos y tutoriales en GitHub.

Este tema puede impartirse en 4-6 horas teóricas y 6-8 horas prácticas, dependiendo del nivel del alumnado y los ejercicios programados. ¿Te interesa que desarrolle alguno de los apartados en más detalle?
