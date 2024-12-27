# Buenas Practicas en GIT
* Agregar un **.gitignore**
* Tener siempre configurado y actualizado el user y el email
* Cada rama creada debe ser especificamente **para resolver un problema o cumplir un objetivo**. No debemos mezclar tareas en una misma rama, para eso se crea otra.
* Cuando se termina de utilziar una rama y se hace el merge, la rama se elimina.
* Las ramas deben tener siempre **nombres descriptivos y kebab-case**
* Antes de hacer un pull request, **se prueba todo en local**, no se debe hacer un pull request en una rama secundaria, se debe hacer el merge con la rama main de nuestro local, y una vez que funciona, hacer el pull request.
* No se debe trabajar en la rama main, p**or cada tarea, una nueva rama**. Si se integra en rama main, pero no se desarrolla en rama main.
* Averiguar sobre distintas maneras de fusionar ramas, **merge, squash y rebase**   
* Los commits deben ser significativos. No se hace un commit cada vez que dejo de usar la computadora, se hace **cada vez que termine una tarea (sub-tarea)**. Estamos haciendo un formulario, terminamos el boton, hacemos un commit 
* Cada commit tiene que tener un mensaje claro y descriptivo de lo reaizado
* Se debe hacer **git pull cada tanto** para mantener actualizado el repositorio
* Esta bueno **utilizar Tags en los commits significativos**
* Mantener el entorno y el historial limpio, utilizar nombres claros, borrar ramas que no se utilizan, ser prolijo con el orden. 