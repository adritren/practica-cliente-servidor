#Docker help
Si queremos construir una imagen de docker necesitaremos crear un fichero con el nombre **dockerfile**


```sh
#Asi construimos una imagen anónima donde el . es la ruta hasta el fichero dockerfile
docker build .

#y así una imagen con nombre
docker build -t ElNombre .
```

Si queremos lanzar un contenedor partiendo de una imagen:
```sh
docker run ElNombre 
#si es una imagen anónima necesitamos el identificador y sería:
docker run id
```