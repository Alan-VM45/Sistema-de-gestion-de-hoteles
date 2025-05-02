# 🏨 Sistema de Gestión de Hoteles

Este proyecto es una aplicación de escritorio desarrollada para gestionar la operación diaria de un hotel. Incluye funciones de administración de habitaciones, personal, mantenimiento, clientes, inventario y más.

---

## 📦 Descarga del Proyecto

Debido al tamaño del proyecto, los archivos están alojados en Google Drive.  
🔽 **Descargá la carpeta completa desde el siguiente enlace:**

➡️ [Ir al proyecto en Google Drive](https://drive.google.com/file/d/1kyNthB3x0-MsnYlHJixwPFyBOWW4_FHt/view?usp=sharing)

> ⚠️ Asegurate de hacer clic en el botón "**Descargar todo**" para evitar errores por archivos faltantes.

---

## 🛠️ Requisitos

- Java JDK 11 o superior  
- NetBeans / IntelliJ / Eclipse  
- [XAMPP](https://www.apachefriends.org/index.html) (para MySQL y phpMyAdmin)  
- Driver JDBC para MySQL (`mysql-connector-java-x.x.x.jar`)

---

## 🚀 Instrucciones de instalación

1. Descargá y descomprimí el proyecto.
2. Abrí la carpeta en tu IDE.
3. Iniciá XAMPP y asegurate de tener corriendo **Apache** y **MySQL**.
4. Entrá a [http://localhost/phpmyadmin](http://localhost/phpmyadmin).
5. Creá una base de datos (por ejemplo `hotel`).
6. ⚠️ **Importante**: Este proyecto **no incluye un archivo `.sql`**, por lo tanto deberás crear las tablas manualmente o desde el mismo sistema si se crean automáticamente al iniciar.
7. Verificá los datos de conexión en el código (generalmente algo como):
   host: localhost
   puerto: 3306
   usuario: root
   contraseña: (en blanco por defecto en XAMPP)
8. Ejecutá `Main.java` para iniciar el sistema.

---

## ❓ ¿Faltan las tablas?

Si no tenés las estructuras de tablas, podés:

- Revisar el código Java y ver cómo se crean (muchas veces hay scripts `CREATE TABLE` embebidos).
- Crear tus propias tablas con los campos que usa el sistema.
- Consultarme y te puedo ayudar a recrear el `.sql` según las clases del proyecto. 💪

---

## 📬 Contacto

Desarrollado por **Agustin Alaniz**  
📧 Email: agustinalaniz0504@gmail.com  
