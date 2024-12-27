# Fusionar Ramas (Merge)
Una vez que se comitean los cambios y se deciden fusionar las ramas se realiza lo siguiente

## Comandos
 
### Fusionar dos ramas (merge)
Debemos estar parados en la rama en la que queremos que se agreguen los nuevos cambios. Por ejemplo, estoy desarrollando en 'rama-auxiliar' y debo pegarlo en 'master', entonces, debo estar parado en master.

`git merge rama-auxiliar`

### Deshacer una fusion (merge)
Debemos regresar al estado anterior a la fusion, por lo que buscamos entre los commits y ponemos ese numero de hash. Los commits no se van a deshacer, se van a separar (se rompe la fusion).

`git reset --hard num_de_hash`

`git reset --hard 7670eec44e`