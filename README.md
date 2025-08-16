# Gestor de Tareas con Flask

Esta es una aplicación web sencilla para gestionar tareas, desarrollada con [Flask](https://flask.palletsprojects.com/) y [Flask‑SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/). Permite crear, listar, completar y eliminar tareas.

## Funcionalidades

- Crear nuevas tareas con título y descripción.
- Visualizar una lista de todas las tareas.
- Marcar tareas como completadas.
- Eliminar tareas.

## Instalación

1. Clona este repositorio:

   ```bash
   git clone https://github.com/Dvstrada/gestor-tareas.git
   cd gestor-tareas
   ```

2. Crea un entorno virtual e instala las dependencias:

   ```bash
   python -m venv venv
   source venv/bin/activate  # En Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. Ejecuta la aplicación:

   ```bash
   flask run
   ```

La aplicación estará disponible en `http://localhost:5000`.

## Estructura

- `app.py`: aplicación principal de Flask.
- `templates/`: plantillas HTML.
- `static/`: archivos estáticos (CSS).
- `requirements.txt`: dependencias.

## Licencia

MIT
