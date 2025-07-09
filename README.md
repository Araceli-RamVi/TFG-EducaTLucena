# TFG-EducaTLucena
Repositorio del TFG - Actualización de la plataforma EducaTLucena (UNIR)

**Actualización de la Plataforma Web EducaTLucena**  
Trabajo Fin de Grado en Ingeniería Informática - UNIR

## Descripción general

Este proyecto corresponde al Trabajo Fin de Grado (TFG) del Grado en Ingeniería Informática de la Universidad Internacional de La Rioja (UNIR). Su objetivo ha sido modernizar y reforzar una plataforma web para la gesti贸n de clases particulares: **EducaTLucena**.

Se han aplicado mejoras visuales mediante el uso de Bootstrap 5 y se ha actualizado el backend a PHP 8, mejorando as铆 la estructura, la seguridad y la compatibilidad con dispositivos m贸viles. Actualmente el sistema permite la gesti贸n de usuarios, tareas, calificaciones y configuraciones asociadas a profesores y alumnos, siendo funcional principalmente para el perfil docente.

---

## 馃幆 Objetivos del proyecto

1. Redise帽ar la parte frontend con un aspecto m谩s moderno e intuitivo.
2. Mejorar la gesti贸n de datos de usuarios con mayor seguridad y cumplimiento del RGPD.
3. Implementar una versi贸n responsive para uso multiplataforma.
4. Solucionar errores de persistencia en configuraciones de usuario.

---

## 馃洜锔?Tecnolog铆as utilizadas

- PHP 8
- Bootstrap 5
- HTML5 / CSS3 / JavaScript
- MySQL
- XAMPP / WAMP (entorno local)
- CKEditor (editor de texto enriquecido en m贸dulo admin)

---

## 馃搧 Estructura del proyecto

```plaintext
/
鈹溾攢鈹€ admin/                     # M贸dulo de administraci贸n (alta, edici贸n, borrado, gesti贸n acad茅mica)
鈹?  鈹溾攢鈹€ bbded/                 # Scripts SQL y funciones de base de datos
鈹?  鈹溾攢鈹€ calendario/           # Componentes para gesti贸n de fechas y tareas
鈹?  鈹溾攢鈹€ ckeditor/             # Editor de texto enriquecido
鈹?  鈹溾攢鈹€ includes/             # Archivos comunes y utilidades
鈹?  鈹溾攢鈹€ js/, imagenes/, assets/
鈹?  鈹斺攢鈹€ *.php                 # Funciones: alta, edici贸n, borrado, consultas, etc.
鈹?鈹溾攢鈹€ Connections/              # Conexiones a base de datos
鈹溾攢鈹€ estilos/, fonts/, js/     # Recursos visuales y scripts comunes
鈹溾攢鈹€ imagenes/                 # Im谩genes generales del sitio
鈹溾攢鈹€ header.php / footer.php   # Cabecera y pie comunes
鈹溾攢鈹€ index.php / login.php     # P谩ginas de entrada y autenticaci贸n
鈹溾攢鈹€ *.php                     # Vistas de error, plantillas, construcci贸n...
```

---

## 鈿欙笍 Instalaci贸n y configuraci贸n

1. Instala **XAMPP** o **WAMP** en tu equipo.
2. Clona o descarga este repositorio en la carpeta del servidor local:
   ```
   C:/wamp/www/new-educatlucena-tfg/
   ```
3. Accede a **phpMyAdmin** y crea la base de datos:
   ```
   educa_t_lucena
   ```
4. Importa el archivo `.sql` correspondiente a la estructura de base de datos (no incluido en este repositorio por privacidad).
5. Configura la conexi贸n a la base de datos en `/Connections/conexion.php`.
6. Accede desde tu navegador a:
   ```
   http://localhost/new-educatlucena-tfg/index.php
   ```
7. Una vez dentro debe loguearse con un usuario con permisos de tipo profesor, puede usarse el siguiente usuario, clicando en el icono de profesores: 

	Usuario: Claudia Password: UNIR@Claudia%2025
8. Con esto podría ir entrando en los diferentes apartados para probar la plataforma, dentro del TFG entre las páginas 41 y 53 se hace un repaso por
   todos los apartados funcionales de la Aplicación Web EducaTLucena.
---

## 馃懁 Autor

**Mar铆a Araceli Ram铆rez Vigo**  
Trabajo Fin de Grado - Grado en Ingenier铆a Inform谩tica  
Universidad Internacional de La Rioja (UNIR)

---

## 馃摎 Palabras clave

PHP 8, Bootstrap 5, plataforma educativa, gesti贸n acad茅mica, responsive, TFG UNIR

---

## 馃 Licencia

Este proyecto ser谩 publicado bajo licencia **MIT**. Libre para uso acad茅mico, educativo o personal.
