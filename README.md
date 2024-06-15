# MyProject

Este proyecto es una aplicación web para gestionar clientes y promociones, utilizando Django para el backend y HTML, CSS y JavaScript puro para el frontend.

## Estructura del Proyecto

La estructura del proyecto es la siguiente:



myproject/
├── mybackend/
│ ├── inventory/
│ │ ├── migrations/
│ │ ├── static/
│ │ │ ├── css/
│ │ │ │ └── styles.css
│ │ │ ├── js/
│ │ │ │ └── scripts.js
│ │ │ └── images/
│ │ ├── templates/
│ │ │ └── inventory/
│ │ │ ├── client_list.html
│ │ │ ├── client_form.html
│ │ │ ├── promotion_list.html
│ │ │ └── promotion_form.html
│ │ ├── init.py
│ │ ├── admin.py
│ │ ├── apps.py
│ │ ├── models.py
│ │ ├── tests.py
│ │ ├── urls.py
│ │ └── views.py
│ ├── mybackend/
│ │ ├── init.py
│ │ ├── settings.py
│ │ ├── urls.py
│ │ └── wsgi.py
│ ├── manage.py
└── venv/