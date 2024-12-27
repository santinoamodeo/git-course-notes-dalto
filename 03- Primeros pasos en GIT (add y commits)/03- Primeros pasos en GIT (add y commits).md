# Primeros pasos en GIT (add y commits)


## Qué es un repositorio?
Es un espacio para guardar archivos, codigo fuente, es el lugar donde guardamos todos


## Areas de un repositorio

### Working Directory

Es el area/directorio donde desarrollamos el software, aqui se hacen modificaciones, se agregana archivos, etc
### Staging Area

Es el area donde guardamos los cambios antes de subir al repositorio, quedan los archivos listos
### Git Area



## Comandos

### Avanzar de carpeta
`cd nombre_carpeta` 

### Retroceder de carpeta
`cd ../` 

**No olvidar barra /**

### Crear carpeta
`mkdir nombre_carpeta`

make directory 

### Eliminar
`rmdir nombre_carpeta`

remove directory 

### Inicializar GIT
`git init`

### Ver archivos dentro de los directorios
`ls` 

### Ver los ademas los archivos ocultos de los directorios
`ls -a`

### Mostrar ruta
`pwd`   

### Subir archivo al Staging Area
`git add nombre_del_archivo`

### Subir mas de un archivo al Staging Area
`git add nombre_del_archivo nombre_del_otro_archivo otro_archivo_mas`

Se deja un espacio entre los nombres de los archivos

### Subir todos los archivos al Staging Area
`git add .`

### Eliminar un archivo del Staging Area
`git rm --cached nombre_del_archivo`

### Eliminar un archivo del Working Directory 
`rm nombre_del_archivo`

### Ver estado del Working Directory y del Staging Area
`git status`

Nos muestra los archivos que salieron del working y que entraron al staging. Tambien informacion de la rama y de los commits.

### Crear un commit
`git commit -m 'nombre del commit' -a`

-m signfica message, se pone una breve descripcion del commit

### Crear un commit con descripcion larga y detallada
`git commit`

Nos abre VSC y alli completamos toda la informacion
