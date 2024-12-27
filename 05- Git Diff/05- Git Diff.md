# Git Diff

## Comandos

### Mostrar informacion de un archivo del ultimo commit
`git show nombre_del_archivo`

### Ver informacion de los commits
`git log`

### Ver los primeros caracteres del hash/id de los repositorio
`git log --oneline`

### Modificar la cantidad de caracteres que se muestra en el git log --oneline

`git config --global core.abbrev 10`

El numero del final, es la cantidad de digitos que queremos ver del hash. 

### Comparar diferencia entre el Staging Area y el Commit
`git diff --staged`

### Comparar diferencias entre commits
`git diff hash_commit_1 hash_commit_2`

`git diff 4c5ae4d59c 4b9a3839d1`

Es util extender los caracteres de los hash, ya que en repositorios con muchos commits, estos hash pueden ser iguales en los primeros digitos, haciendo que se complique la forma de identificarlos.

### Ver solamente los archivos que cambiaron entre dos commits
`git diff --name-only hash_commit_1 hash_commit_2`

`git diff --name-only 4c5ae4d59c 4b9a3839d1`

### Ver linea por linea que cambio en los archivos entre dos commits
`git diff --word-diff hash_commit_1 hash_commit_2`

`git diff --word-diff 4c5ae4d59c 4b9a3839d1`
