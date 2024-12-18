# app_numero_uno
# Gestión de Tareas - Aplicación con Streamlit y SQLite

## Descripción
Esta aplicación permite a los usuarios gestionar sus tareas diarias. Los usuarios pueden agregar nuevas tareas, listar todas las tareas, marcar tareas como completadas, eliminar tareas completadas, y exportar e importar tareas desde un archivo JSON. El almacenamiento de tareas se realiza en una base de datos SQLite, que proporciona persistencia de datos.

## Funcionalidades
1. **Agregar Tareas**:
   - Permitir al usuario agregar nuevas tareas con un título y una descripción.
   
2. **Listar Tareas**:
   - Mostrar todas las tareas agregadas con su estado (pendiente o completada).
   
3. **Marcar Tareas como Completadas**:
   - Permitir al usuario marcar una tarea como completada.
   
4. **Eliminar Tareas**:
   - Permitir al usuario eliminar tareas completadas.
   
5. **Exportar e Importar Tareas con JSON**:
   - Exportar las tareas a un archivo JSON.
   - Importar las tareas desde un archivo JSON.

6. **Interfaz Gráfica**:
   - Utiliza Streamlit para crear una interfaz gráfica intuitiva para interactuar con las tareas.

## Requisitos Técnicos
- **Lenguaje de programación**: Python
- **Módulos de Python**: `sqlite3`, `json`, `streamlit`
- **Base de datos**: SQLite
- **Interfaz gráfica**: Streamlit
- **Persistencia de datos**: SQLAlchemy (no utilizado en este proyecto, se cambió a SQLite)

## Instalación
1. Asegúrate de tener Python instalado en tu sistema. Puedes descargarlo desde [Python.org](https://www.python.org/downloads/).
   
2. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/gestion-tareas
   cd gestion-tareas
