# Git restore y checkout y más

## Comandos

### Restaurar un archivo borrado
`git restore archivo.txt`

Esto, siempre y cuando se haya hecho un commit donde se encuentre este archivo, pq lo estoy borrando local, pero ya paso por el staging area.

### Volver al ultimo commit en un archivo (Working Directory)
`git checkout archivo.txt`

Mientras no se haya hecho un nuevo commit, podemos volver los cambios al ultimo commit realizado. Es todo a nivel de Working Directory, si lo subo a Staging Area, no funciona.

### Volver al ultimo commit (Staging Area)
`git reset --hard`

Al ser hard, me elimina lo que yo tengo en staging area, volviendo a los cambios del ultimo commit, hay que tener cuidado cdo se usa.

### Cambiar el nombre de un archivo
`git mv nombre_archivo_viejo nombre_archivo_nuevo`

Se separa el nombre viejo del nuevo

### Ver git status acortado, mas claro
`git status s-`

`git status --short`