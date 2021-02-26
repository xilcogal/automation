# Automatización de servicios de la Administración Pública

by Xose Eijo

## Introducción

En este documento se recogen algunos de los servicios de interoperatividad con las Administraciones Públicas del estado. El objetivo del documento es analizar como se realiza esta interoperatividad y que posibilidades de automatización presentan a través de servicios backend o RPA.

Los servicios que se analizaran en este documento son:

- Certific@2 del Sepe.
- Contrat@ del Sepe.
- Siltra de la Seguridad Social.
- Modelo 111 de la Agencia tributaria.

## Descripción de los servicios

### Certific@2

Este servicio permite el envío a través de Internet, por parte de las empresas, de los **certificados de empresa de ceses por suspensión o extinción de la relación laboral**.

#### Interoperatibilidad

El servicio Certific@2 ofrece dos medios de comunicación:

- **Sede electrónica:** a través del portal se pueden entregar los certificados de dos formas:
  - subida del fichero XML con los datos de los empleados.
  - cubriendo el formulario web, empleado a empleado.
- **Servicio Web**: este es medio desatendido para la comunicación de los certificados de empresa. El sistema del empresario debe generar el fichero XML y comunicarlo al Servicio Web.

#### Otra información relevante

La sede electrónica posibilita el uso de un entorno de pruebas para la puesta a punto de los ficheros. El entorno requiere identificación de la empresa.

La documentación para la generación del fichero XML y el desarrollo del cliente de `web service` se encuentra en el portal de Certific@2 por lo que es necesario identificarse para descargar esta información.

### Contrat@

