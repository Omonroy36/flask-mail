Preparar entorno virtual
##### Solo si tienen mas de una version de python
```
$ pipenv --python="3.x" 
```
##### Crear el entorno virtual con la version por defecto de python
```
$ pipenv shell 
```
Instalar las librerias necesarias dentro del Pipfile
```
$ pipenv install
```
Comandos para la base de datos
### Ejecutar solo la primera vez si no tienen la carpeta migrations
```
$ flask db init 
```
### Ejecutar para crear las migraciones 
```
$ flask db migrate
```

### Ejecutar para enviar las migraciones hacia la base de datos
```
$ flask db upgrade
```

Iniciar el servidor
```
$ python app.py runserver
```
