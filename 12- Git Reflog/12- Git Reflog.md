# Git Reflog
Es una herramienta que lleva registro de todos los commits realizados, todos los lugares donde HEAD ha apuntado.

* Los commits no se borran instantaneamente, **se borran sus referencias**

## Comandos

### Como recuperar un commit del que perdi su numero de hash
`git reflog`

* Voy a tener un listado de los commits y donde se ha movido HEAD. 
* Copio el numero de hash del commit perdido y lo recupero asi

`git reset --hard numero_de_hash`