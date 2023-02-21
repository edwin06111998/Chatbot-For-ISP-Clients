
<h1 align="center">  
  <img src="https://user-images.githubusercontent.com/54828392/220443356-ec007848-6841-41bd-bfb4-4264fbdf929d.png" alt="Chatbot" width="500"></a>
  <br>
</h1>

<h4 align="center">Configurado para WhatsApp y Facebook Messenger</h4>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#download">Download</a> •
  <a href="#credits">Credits</a> •
  <a href="#related">Related</a> •
  <a href="#license">License</a>
</p>

<p align="center">
<img width="1000" src="https://github.com/edwin06111998/Imagenes/blob/main/Proceso%20Chatbot/Proceso%20Chatbot.gif?raw=true">
</p>

## Tabla de contenidos

- [Introducción](#introduction)
- [Funciones](#features)
- [Retroalimentación](#feedback)
- [Contribuidores](#contributors)
- [Proceso de construcción](#build-process)
- [Contacto](#acknowledgments)

## Introducción

Asistente virtual capaz de interpretar mensajes con Inteligencia Aritificial, permitiendo obtener la información de clientes de un ISP accediendo mediante API al sistema de administración de clientes. El Chatbot es capaz de procesar recibos y verificar su validez, acceder a los routers Wi-Fi para ver dispositivos conectados, cambiar nombre y clave Wi-Fi, además, permite generar tickets de atención al cliente.

Funciona con un sistema de botoneras que brinda una mejor experiencia de usuario.

**Dispinible para WhatsApp, Facebook Messenger, Telegram, Instagram**

## Funciones

Estas son algunas de las características del sistema de monitoreo:

* Interpretar contexto de mensajes mediante Inteligencia Artificial
* Plataforma para administrar conversaciones
* Envío de mensajes masivos
* Procesar pagos analizando los vóuchers
* Ver facturas pendientes
* Configurar router Wi-Fi de manera remota (nombre, clave, dispositivos conectados, ocultar red)
* Solicitar ticket de atención al cliente
* Actualizar información de cliente

<p align="center">
  <h3>Menú de inicio</h3>
  <img width="1000" src="https://raw.githubusercontent.com/edwin06111998/Imagenes/main/Proceso%20Chatbot/Inicio.png?token=GHSAT0AAAAAAB64XCUL5WHWTLDTB3ZXRWLMY7VI2CA">
</p>

## Retroalimentación

Siéntete libre de comentarme tu experiencia utilizando este sistema, puedes escribir al siguiente correo: edwin06111998@gmail.com. Tus comentarios son importantes para seguir haciendo robusto este sistema.

## Contribuidores

Este proyecto ha sido desarrollado únicamente por mí (Edwin Veloz).

## Proceso de construcción

- Clona o descarga el repositorio
- Crea una aplicación en Facebook para usar la API de WhatsApp
- Obtén un token permanente y el ID de la aplicación
- Crea las plantillas en Facebook para los mensajes de alerta
- Ingresa el token y ID en el archivo send_message.py
- Modifica el "filepath" ingresando la ruta del repositorio en los archivos ping.py y antennas.py
- Ingresa las IPs en el archivo ips.txt y los destinatarios en el archivo numbers.txt
- Ejecuta ping.py y antennas.py

Importante: para ejecutar el código 24/7, puedes implementarlo en un servidor Linux y usar comandos como "crontab -e" para ejecutar el código cada determinado tiempo.

## Contacto

- LinkedIn: www.linkedin.com/in/edwin-veloz-2153a9137
- Correo: edwin06111998@gmail.com
