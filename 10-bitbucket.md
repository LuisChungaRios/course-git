# Clase 10 
uso del repositorio bitbucket 
link: `https://bitbucket.org ` 

## Comandos utilizados
1. Mostrar todos los repositorios: `git remote -v`.
2. Cambiar de nombre al repositorio: `git remote rename old_name new_name`.
3. Eliminar un repositorio: `git remote remove name_repository`
4. Agregar un nuevo repositorio: `git remote add name_repository url-direction`.
5. Subir los archivos locales al repositorio: `git push -u name_repository master`.
Ejemplo:
```
git remote add bitbucket  https://LuisChunga@bitbucket.org/LuisChunga/curso-git.git
git push -u bitbucket master 
```