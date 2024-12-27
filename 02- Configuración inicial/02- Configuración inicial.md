# Configuración inicial

## Descarga 
Desde la pagina oficial de GIT, sistema operativo y version necesaria. Next a todas las ventanas.

## Jerarquias de configuracion

### Area Local
Afecta unicamente al repositorio particular
`git config --local`

### Area Global
Afecta a todos los repositorios de un usuario
`git config --global`

### Area System 
Afecta a toda la computadora
`git config --system`

---
## Comandos
### Poner el nombre
`git config --global user.name "Santino Amodeo"`

### Poner el email
`git config --global user.email "santinoamodeoph@gmail.com"`

### Ver listado de configuraciones a nivel system
`git config --list`

### Ver listado de configuraciones a nivel global
`git config --global --list`

### Ver listado de configuraciones a nivel local
`git config --local  --list`

### Configurar GIT para Visual Studio Code
`git config --global core.editor "code --wait"`

### Mejorar color de salidas a pantalla
 `git config --global color.ui true`

### Salto de linea y volver al inicio automatico 
 **SOLO WINDOWS**
 
 `git config --global core.autocrlf true`
 
 Con esto logramos no tener errores de compatibilidad con MAC y Linux

### Salto de linea y volver al inicio automatico 
 **SOLO MAC y LINUX**
 
 `git config --global core.autocrlf input`
 
 Con esto logramos no tener errores de compatibilidad con Windows

