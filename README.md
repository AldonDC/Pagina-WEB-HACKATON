# MyProject

Este proyecto es una aplicación web para gestionar clientes y promociones, utilizando Django para el backend y HTML, CSS y JavaScript puro para el frontend.

## Estructura del Proyecto

La estructura del proyecto es la siguiente:

El proyecto myproject está estructurado con un directorio principal mybackend que contiene la configuración del proyecto Django, incluyendo archivos como settings.py, urls.py y wsgi.py, junto con el script de gestión manage.py. Dentro de mybackend, se encuentra la aplicación inventory que maneja la lógica del CRUD para clientes y promociones. La aplicación inventory incluye subdirectorios para migrations, static (con subdirectorios para CSS, JS e imágenes), y templates (con plantillas HTML para listar, crear y editar clientes y promociones). Además, inventory contiene archivos clave como models.py para definir los modelos de datos Client y Promotion, views.py para las vistas del CRUD, urls.py para las rutas, admin.py para la configuración del administrador y apps.py para la configuración de la aplicación. El entorno virtual venv se utiliza para gestionar las dependencias del proyecto.