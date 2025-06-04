# Proyecto API
Este repositorio contiene una API desarrollada en PHP como parte de un sistema de gestión web. La API está diseñada para manejar autenticación, gestión de usuarios y comunicación con una base de datos MySQL.

## Requisitos
- PHP versión 8.2.12 o superior
- Composer instalado en el sistema
- Servidor local (XAMPP)
- Base de datos MySQL

## Instalación
1. Clona el repositorio:  
   ```bash
   git clone https://github.com/HazielDev12/proyecto_api.git
2. Actualiza composer
   ```bash
   composer update

 ## Configuración de correo electrónico
Para que el sistema pueda enviar correos electrónicos (recordatorios), debes configurar una cuenta de correo válida en el archivo donde se utiliza PHPMailer.
En el código, asegúrate de completar estos parámetros dentro de la función send() en EmailController.php:
   ```bash
$mail->Username = 'tu_correo@gmail.com';  // Coloca aquí el correo de Gmail desde donde se enviarán los emails
$mail->Password = 'tu_contraseña_o_password_de_app'; // Tu contraseña o password de aplicación generada en Gmail
