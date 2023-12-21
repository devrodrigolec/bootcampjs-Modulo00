# Laboratorio Módulo 00 Git

## Creando Repositorio

- Para crear el repositorio accedemos a la consola y utilizamos el comando ```mkdir -nombre-del-repositorio-```

## Creamos el archivo readme.md

- Creamos el archivo readme.md desde visual studio code o desde la consola con el comando ```touch readme.txt``` 

## Agregamos los cambios realizados al stagin

- Agregamos los cambios realizados al stagin con el comando ```git add .```

## Hacemos nuestro primer commit

- Hacemos nuestro primer commit con el comando ```git commit -m "-mensaje-"``` y utilizamos un mensaje personalizado para describir los cambios hechos en el commit. 

## Creamos nuestro repositorio en GitHub 
- Para crear nuestro repositorio en GitHub hacemos click en "New", le damos un nombre al repositorio, y en este caso no creamos un archivo readme porque ya lo estamos creando desde el repositorio local.

## Enlazamos nuestro repositorio remoto con el repositorio local
- Para enlazar nuestro repositorio remoto con nuestro repositorio local copiamos el enlace SSH y utilizamos el comando ```git remote add origin -Enlace-SSH-Del-Repositorio-```

## Creamos un nuevo archivo index.html
- Creamos el archivo index.html y le colocamos un elemento H1 con el texto "Nuevo Archivo".
- Agregamos el archivo al stagin con ```git add .``` y hacemos el comit con ```git commit -m "agregando index.html"```

## Hacemos el primer Push al repositorio Remoto
- Para hacer el primer push al repositorio remoto utilizamos el comando ```git push -u origin main```

## Creamos una rama con el nombre "development"
- Para crear una rama utilizamos el comando ```git branch development ```
- Cambiamos a la rama development utilizando el comando ```git checkout development```
- Realizamos un cambio en el archivo index.html agregando un elemento H2 con el texto "Cambios hechos desde rama development".
- Agregamos a stagin y hacemos el commit en la rama development.
- Subimos los cambios al repositorio remoto con el comando ```git push -u origin development```

## Realizamos un merge en la rama Main
- Para realizar un merge con la rama main, primero, debemos cambiar a la rama main con el comando ```git checkout main```
- Luego utilizamos el comando ```git merge development```
- Si no existen conflictos entre los archivos, se realizará el merge automáticamente. 
- Luego subimos los cambios al repositorio remoto con el comando ```git push```
