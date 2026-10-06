# Hardening inicial de una máquina virtual

**Alumno:** Julian Bosio

Práctica de configuración segura de base sobre una máquina virtual en Oracle VirtualBox con Kali Linux.

## Entregable

📄 [Reporte_Hardening_Bosio_Julian.pdf](Reporte_Hardening_Bosio_Julian.pdf)

## Pasos realizados

1. Creación de la máquina virtual en VirtualBox.
2. Configuración del adaptador de red en modo **NAT**.
3. Instalación del sistema operativo (Kali Linux).
4. Creación de un usuario sin privilegios (`invitado`, fuera del grupo `sudo`).
5. Actualización completa del sistema (`apt update` + `apt full-upgrade`).
6. Snapshot **"Hardening inicial"** con la máquina apagada.

El reporte incluye las capturas de cada paso y la explicación de por qué cada medida es importante para la seguridad.
