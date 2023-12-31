# Coder-primer-repositorio

## Entornos virtuales 

Un entorno virtual en Python es una herramienta 
que te permite crear un espacio aislado donde puedes instalar 
y manejar las dependencias (bibliotecas y versiones de Python) 
específicas para un proyecto en particular, sin afectar al sistema global

`pip list` muestra las bibliotecas instaladas en el entorno virtual o global

¿Cómo crear un entorno virtual?
`python -m venv .venv`  -> Windows
`python3 -m venv .venv`  -> Linux

¿Cómo activar el entorno virtual?
`.\.venv\Scripts\activate` (Windows Powershell)
`source .venv/bin/activate` (Linux o Mac)

## Instalación Django
`pip install django`

## Comandos: crear nuestra aplicación Django
- Creo una carpeta `project`
- `mkdir project`

- Accedemos a la carpeta project
- `cd project`

- Crear el proyecto Django 
- `django-admin startproject config .`

- Ejecutar el servidor:
- `python manage.py runserver`

-  Crear un archivo views.py dentro de config. (MTV = Models Templete Views)
- `click derecho en config, nuevo archivo, lo llamamos views.py`
