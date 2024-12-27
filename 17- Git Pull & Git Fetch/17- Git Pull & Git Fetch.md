# Git Pull & Git Fetch

Git Pull se utiliza para bajar al LOCAL los **cambios realizdos en el SERVIDOR**

## Comandos
### Bajar cambios del servidor al local
`git pull`
`git pull origin main`

### Tener una vista previa de los cambios del servidor para bajarlos a local y aceptarlos como vienen
1. `git fetch`
2. `git switch --detach origin/main`
3. `git pull`

### Tener una vista previa de los cambios del servidor para bajarlos a local y **realizarle modificaciones**
1. `git fetch`
2. `git switch --detach origin/main`
3. `git switch -c exp-branch origin/main`
4. Realizar todas las modificaciones
5. Hacer commits
6. `git merge exp-branch` estando parados en main
7. `git branch -d exp-branch` si no nos deja borrar la -D va mayus