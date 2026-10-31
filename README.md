# Blog Django

Proyecto base de un blog web desarrollado con Django 6.1.

## Descripción

Este repositorio contiene la estructura inicial de un proyecto Django para construir un blog.
Incluye la configuración base del proyecto (`blog_project`), con idioma español de Argentina
(`es-ar`) y zona horaria `America/Argentina/Buenos_Aires`, y una aplicación llamada `posts`
para manejar las publicaciones.

## Requisitos

- Python 3.12 o superior
- Git

## Instalación

1. Clonar el repositorio:

```bash
git clone https://github.com/TU_USUARIO/blog_django.git
```

2. Entrar a la carpeta del proyecto:

```bash
cd blog_django
```

3. Crear el entorno virtual:

```bash
python -m venv venv
```

4. Activar el entorno virtual:

- En Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

- En Windows CMD:

```cmd
venv\Scripts\activate.bat
```

- En Linux o macOS:

```bash
source venv/bin/activate
```

5. Instalar las dependencias:

```bash
pip install -r requirements.txt
```

## Ejecución

Levantar el servidor de desarrollo:

```bash
python manage.py runserver
```

Abrir en el navegador: http://127.0.0.1:8000/

Para detener el servidor, presionar `Ctrl + C`.

## Estructura del proyecto

```
blog_django/
├── manage.py
├── requirements.txt
├── README.md
├── .gitignore
├── blog_project/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
└── posts/
    ├── __init__.py
    ├── admin.py
    ├── apps.py
    ├── models.py
    ├── tests.py
    ├── views.py
    └── migrations/
```

## Aplicaciones

- `posts`: aplicación principal, inicial para manejar las publicaciones del blog.

## Dependencias

- Django 6.1.2
- asgiref 3.13.0
- sqlparse 0.6.0
- tzdata 2026.6
