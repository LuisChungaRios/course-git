# Curso Git desde cero 
## Clase 1 Introduccion 

### Que es git ? 
Git es un software de control de versiones 

## Flujo de trabajo en git 
1. Modificas una serie de archivos en tu directorio de trabajo.
2. Preparas los archivos,añadiendolos a tu área de preparación 
3. Confirmas los cambios, lo que toma los archivos tal y como están en el área de preparación y almacena esa copia instantaneamente de manera permanente en tu directorio de Git

### Comandos para configurar git.

Nombre de usuario: `git config --global user.name "your_name"`

Email de usuario : `git config --global user.email "your_email"`
Editor de codigo : `git config --global core.editor your_editor_code`

### Comandos adicionales: 
 Mostrar las configuraciones: `git config --list`
 Mostrar las configuraciones del usuario: `git config --user`
 Mostrar las configuraciones en el editor de codigo: `git config --editor`

 ### Comandos de ayuda en git: 
 `git config --help`
 `git help config`

## Clase 2: Iniciar Git 
### Comandos 
Despues de configurar git, podemos empezar a trabajar.
Iniciar git : `git init` 

Estado del area de trabajo : `git status`

Agregar un archivo a la zona de preparacion: `git add nombre_archivo`

Agregar todos los arhivos a la zona de preparación: `git add .`

Agregar todos los archivos que estamos siguiendo: `git add -A`

Sacar el archivo de la zona de preparación: `git reset HEAD name_file`

Confirmar cambios en git: `git commit -m "message_your_description of commit"`

Ver el historial de los commit: `git log`

Ver el historial de los commit en una linea: `git log --oneline`

Otros comandos para ver el historia:
`git log --oneline --decorate --all --graph`

Mostrar las diferencias de un arhivo en zona de preparacion con el ultimo commit: 
`git diff`

Mostrar la diferencia entre un mismo archivo que ya preparamos, y lo que no se ah preparado  `git diff --staged`

Cambiar la descripcion del ultimo commit: `git commit --amend`

Ignorar los archivos en git: Creamos un archivo con el nombre `.gitignore` dentro de ese archivo colocamos el nombre de los archivos o carpetas.