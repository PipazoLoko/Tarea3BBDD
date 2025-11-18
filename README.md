# Tarea 3 - MONGODB

**Alumnos**:
- Felipe Carrasco Patelli - 202473522-5
- Felipe Luengo Bascuñan - 202473509-8

## Descripción del proyecto
Investigar y aplicar los conceptos básicos sobre el gestor de base de datos NoSQL MongoDB, utilizando herramientas como Docker para desplegar los servicios, MongoDB Query Language (MQL) y Python.
En el archivo `pymongo-202473522-5-202473509-8.ipynb` se encuentran las operaciones solicitadas en la tarea, utilizando la librería `pymongo` para interactuar con la base de datos MongoDB.
En el archivo `prueba.ipynb` se encuentran las pruebas de consistencia y alta disponibilidad.

## Instrucciones para ejecutar el proyecto
Para ejecutar el proyecto, siga los siguientes pasos:

```bash
# Crea y activa el entorno virtual
python -m venv venv
source venv/bin/activate
# Instala las dependencias
pip install -r requirements.txt
```

La carpeta de `DiscursosOriginales` debe estar en el mismo directorio que los notebooks para que el código funcione correctamente. Para que pueda acceder a los archivo de la siguiente forma:

```bash
./DiscursosOriginales/nombre_del_archivo.txt
```

Luego, para iniciar y detener los contenedores de Docker, utilice los siguientes comandos:
```bash
# Iniciar contenedores
docker-compose -f deploy-202473522-5-202473509-8.yml up -d
```

```bash
# Detener contenedores
docker-compose -f deploy-202473522-5-202473509-8.yml down -v
```