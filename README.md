Gestor de Tareas

Descripción

El Gestor de Tareas es una aplicación de escritorio desarrollada en Python utilizando la biblioteca Tkinter y SQLAlchemy. Permite a los usuarios gestionar sus tareas de manera eficiente, con funcionalidades como agregar tareas, marcar tareas como completadas, eliminar tareas completadas, y exportar e importar datos en formato JSON.

Características

Agregar Tareas: Permite agregar tareas con un título y una descripción opcional.

Completar Tareas: Marca las tareas seleccionadas como completadas.

Eliminar Tareas Completadas: Elimina todas las tareas que ya han sido marcadas como completadas.

Exportar Tareas: Guarda todas las tareas en un archivo tarea.json.

Importar Tareas: Carga tareas desde un archivo tarea.json.

Interfaz de Usuario: Interfaz limpia y organizada con una barra de menú que permite acceder a todas las funcionalidades.

Requisitos del Sistema

Python 3.6 o superior.

Biblioteca SQLAlchemy.

Biblioteca Tkinter (incluida por defecto en la mayoría de las distribuciones de Python).

Instalación

Clona este repositorio o descarga los archivos.

Asegúrate de tener Python instalado en tu sistema.

Instala las dependencias ejecutando el siguiente comando:

pip install sqlalchemy

Ejecuta el archivo GestordeTareas.py:

python GestordeTareas.py

Uso

Agregar una Tarea: Escribe el título y la descripción de la tarea en los campos correspondientes y haz clic en el botón "Agregar Tarea".

Completar una Tarea: Selecciona una tarea en la lista y usa la opción del menú "Completar Tarea".

Eliminar Tareas Completadas: Selecciona la opción del menú "Eliminar Tareas Completadas".

Exportar Tareas: Selecciona la opción del menú "Exportar Tareas" para guardar las tareas en un archivo JSON.

Importar Tareas: Selecciona la opción del menú "Importar Tareas" para cargar tareas desde un archivo JSON.

Estructura del Proyecto

GestordeTareas.py: Archivo principal que contiene el código de la aplicación.

GestordeTareas.db: Base de datos SQLite que almacena las tareas.

tarea.json: Archivo JSON utilizado para exportar e importar tareas.

gt-logo.ico: Archivo que contiene el icono de la aplicación.
