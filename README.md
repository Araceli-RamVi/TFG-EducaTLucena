# TFG-EducaTLucena
Repositorio del TFG - Actualización de la plataforma EducaTLucena (UNIR)

**Actualización de la Plataforma Web EducaTLucena**  
Trabajo Fin de Grado en Ingeniería Informática - UNIR

## Descripción general

Este proyecto corresponde al Trabajo Fin de Grado (TFG) del Grado en Ingeniería Informática de la Universidad Internacional de La Rioja (UNIR). Su objetivo ha sido modernizar y reforzar una plataforma web para la gestión de clases particulares: **EducaTLucena**.

Se han aplicado mejoras visuales mediante el uso de Bootstrap 5 y se ha actualizado el backend a PHP 8, mejorando así la estructura, la seguridad y la compatibilidad con dispositivos móviles. Actualmente el sistema permite la gesti贸n de usuarios, tareas, calificaciones y configuraciones asociadas a profesores y alumnos, siendo funcional principalmente para el perfil docente.

---

## Objetivos del proyecto

1. Rediseñar la parte frontend con un aspecto más moderno e intuitivo.
2. Mejorar la gestión de datos de usuarios con mayor seguridad y cumplimiento del RGPD.
3. Implementar una versión responsive para uso multiplataforma.
4. Solucionar errores de persistencia en configuraciones de usuario.

---

## Tecnologías utilizadas

- PHP 8
- Bootstrap 5
- HTML5 / CSS3 / JavaScript
- MySQL
- XAMPP / WAMP (entorno local)
- CKEditor (editor de texto enriquecido en módulo admin)

---

## Estructura del proyecto

```new-educatlucena-tfg
/
- admin/                     # Módulo de administración (alta, edición, borrado, gestión académica)
	- bbdd/                 # Scripts SQL y funciones de base de datos
	- calendario/           # Componentes para gestión de fechas y tareas
	- ckeditor/             # Editor de texto enriquecido
	- includes/             # Archivos comunes y utilidades
	- js/, imagenes/, assets/
	-  *.php                 # Funciones: alta, edición, borrado, consultas, etc.
-Connections/              # Conexiones a base de datos
- estilos/, fonts/, js/     # Recursos visuales y scripts comunes
- imagenes/                 # Imágenes generales del sitio
- header.php / footer.php   # Cabecera y pie comunes
- index.php / login.php     # Páginas de entrada y autenticación
- *.php                     # Vistas de error, plantillas, construcción...
```

---

## Instalación y configuración

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

## Autora

**María Araceli Ramírez Vigo**  
Trabajo Fin de Grado - Grado en Ingeniería Informática  
Universidad Internacional de La Rioja (UNIR)

---

## Palabras clave

PHP 8, Bootstrap 5, plataforma educativa, gestión académica, responsive, TFG UNIR

---

## Licencia

Este proyecto será publicado bajo licencia **MIT**. Libre para uso académico, educativo o personal.
