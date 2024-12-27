# Ramas (Branches)
Las ramas son lineas independientes donde los desarrolladores pueden trabajar sin afectar los cambios ni el trabajo de demas desarrolladores ni el flujo normal del sistema.

Luego si el trabajo realizado es correcto, se fusionan (**merge**) las ramas, quedando los nuevos cambios en funcionamiento.

Tambien, se tiene en cuenta que son **temporales**, solo se crean para algo especifico, para una/s tarea/s en particular y luego **la rama se elimina** . Puede no eliminarse en caso de que a futuro se siga trabajando en esa tarea particular, por mas de que ya se haya completado.

## IMPORTANTE
**KEBAB CASE =** `esto-es-kebab-case`

**SNAKE CASE =** `esto_es_snake_case`

**CAMEL CASE =** `estoEsCamelCase`

## Comandos

### Ver las ramas
`git branch`

### Crear nueva rama
`git branch nombre-rama`

Las ramas se escriben en **KEBAB CASE**

### Moverse de rama
`git switch nombre-rama` **SE RECOMIENDA HACERLO ASI**

`git checkout nombre-rama` Es viejo, pero funciona.

### Crear nueva rama y moverse directamente 
`git switch -c nombre-rama`

### Eliminar una rama 
**Nunca hay que estar parado en la rama que eliminamos**

`git branch -d nombre-rama`

### Renombrar una rama distinta a la que estoy parado
`git branch -m nombre-rama-viejo nombre-rama-nuevo`

Primero el nombre actual de la rama, luego el que queremos que tenga

### Renombrar la rama donde estoy parado

`git branch -m nombre-rama-nuevo` 
