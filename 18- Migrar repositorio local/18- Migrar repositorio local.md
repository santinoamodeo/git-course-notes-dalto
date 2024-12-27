# Migrar repositorio local


## Comandos

### Crear un archivo
`touch arvhivo.formato`

`touch archivo.txt`

### Eliminar un archivo
`rm archivo.formato`
`rm archivo.txt`

### Migrar un repositorio local a remoto (servidor)
`git remote add origin https://github.com/santinoamodeo/nuevo-repo.git`

`git branch -M main`

`git push -u origin main` al poner -u, la proxima que hagamos un push, nonecesitamos especificar origin main