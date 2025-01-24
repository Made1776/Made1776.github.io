
# Instructivo de Servidores Red Hat - CentOS

## Índice
1. [Introducción](#introducción)
2. [Requisitos Previos](#requisitos-previos)
3. [Instalación](#instalación)
4. [Configuración Básica](#configuración-básica)
5. [Gestión de Paquetes](#gestión-de-paquetes)
6. [Seguridad](#seguridad)

---

## Introducción
Este documento proporciona una guía básica para la gestión de servidores Red Hat y CentOS, cubriendo desde la instalación hasta la seguridad básica del sistema.

---

## Requisitos Previos
Antes de comenzar, asegúrese de que su hardware es compatible y que tiene acceso a internet para descargar actualizaciones y paquetes necesarios.

---

## Instalación
La instalación de CentOS es sencilla. Siga las instrucciones en pantalla y seleccione las opciones que mejor se adapten a sus necesidades.

**_Nota:_** Recuerde siempre verificar la integridad de la imagen ISO antes de proceder con la instalación.

---

## Configuración Básica
Configurar su servidor CentOS incluye ajustar la zona horaria, configurar la red, y establecer políticas de seguridad.


## Establecer la zona horaria
timedatectl set-timezone America/New_York

## Configurar la red
nmcli dev status

---

## Gestión de Paquetes
CentOS utiliza `yum` y `dnf` como gestores de paquetes para instalar y actualizar software.

### Ejemplo de instalación de un paquete
```bash
sudo yum install httpd
```

> **Advertencia:** Asegúrese de solo instalar software de fuentes confiables para evitar problemas de seguridad.

---

## Seguridad
Mantener su servidor seguro es crucial. Asegúrese de configurar un firewall y mantener el sistema actualizado.

### Lista de comprobación de seguridad básica
1. Configurar el firewall
2. Establecer contraseñas seguras
3. Actualizar el sistema regularmente

*Actualizaciones del sistema:*
```bash
sudo yum update
```

**_Nota importante:_** Siempre haga copias de seguridad antes de realizar cambios importantes en el sistema.

---

[CentOS Official Website](https://www.centos.org)

---