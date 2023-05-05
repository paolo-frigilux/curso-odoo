# Clase 05-05-2023

## Introducción

- Haremos el ejercicio del sitio web
- Vamos a crear un controlador, tomando la cabecera de otro módulo, esta cabecera es el comienzo de `controllers/main.py`
- Esta función principal puede recibir parámetros propios (personalizados)
- En el return renderiza la vista
- Hay otro directorio llamado views
- `t-call="website.layout"` en `views/web.xml`
    - se usa para importar el resto de los botones del sitio web
- Esta vista se tiene que agregar en el `__manifest__.py` 
- en `__init__.py` importamos main from . así `from . import main`
- En la carpeta `static/src/css` creamos un archivo `hojas.css`
    - También debe existir la carpeta `static/src/js`
- En la versión 14 debemos crear otro archivo `views/template.xml`
    - Se puede buscar uno ya usado de otro módulo para ahorrar tiempo, ahí vemos el tag `link` en donde se especifíca la ubicación.

## Tarea
- 