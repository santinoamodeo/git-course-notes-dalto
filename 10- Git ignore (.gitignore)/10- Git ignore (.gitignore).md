# Git ignore (.gitignore)
Es un archivo que se agrega para ignorar la subida de archivos inncesearios a los commits y al repositorio.

## Escribir .gitignore
* **Comentarios** = #Esto es un comentario
* Ignorar **un archivo** = nombre_del_archivo.formato
* Ignorar **todos los archivos de un formato** = *.formato
* **NO** ignorar **un archivo de un formato ignorado** = !nombre_del_archivo.formato
* Ignorar una **carpeta con su contenido** = nombre_carpeta/
* Ignorar **todos los archivos terminados en ).formato** = *).formato 
* **NO** ignorar una **foto dentro de una carpeta ignorada** = !fotos/nombre_de_la_foto.formato

## Comandos

### Ver todos los archivos que existen dentro de un commit cualquiera
`$ git ls-tree -r --name-only hash-del-commit`

### Ver todos los archivos que existen dentro del ULTIMO commit
`$ git ls-tree -r --name-only HEAD`

**HEAD** nos referencia el ultimo commit, sin necesidad de poner su hash

### Crear un .gitignore_global que afecte a todos los repositorios
Se suele hacer para que siempre se ignoren los mismos archivos, pq siempre los voy a tener en los repos. Por ejemplo, un .txt de anotaciones.

Creo en una **direccion 'X'** un archivo **.gitignore_global**, lo configuro con lo que quiero ignorar

En la bash, configuramos asi:
`git config --global core.excludesfile ruta_del_archivo_x`
