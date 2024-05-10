## Git-Practice

### Comandos básicos:

- **git init:** Se utiliza para iniciar un nuevo repositorio en la carpeta especificada.
  
- **git status:** Muestra el estado de los archivos en el repositorio, incluyendo los cambios y el estado de la rama actual.

- **git add:** Agrega archivos al área de staging.
  - `git add .`: Agrega todos los archivos al área de staging.

- **git commit -m "mensaje":** Guarda los cambios realizados en el área de staging en el repositorio.
  
- **git show:** Muestra los cambios realizados en una versión específica.

- **git log:** Muestra el registro de commits.

- **git checkout:** Permite cambiar entre ramas o revertir cambios en archivos específicos.

- **git diff:** Muestra las diferencias entre versiones o ramas.

### Comandos para gestión de cambios:

- **git reset xxxxxxxxxxxxxxxxxxxxxx --hard:** Revierte los cambios realizados en el repositorio al commit especificado, eliminando los cambios posteriores.
  
- **git reset xxxxxxxxxxxxxxxxxxxxxx --soft:** Revierte los cambios realizados en el último commit, pero mantiene los cambios en el área de staging.

- **git reset xxxxxxxxxxxxxxxxxxxxxx HEAD:** Mueve los archivos del área de staging a untracked.

### Comandos para trabajar con repositorios remotos:

- **git clone url:** Clona un repositorio remoto en el directorio de trabajo local.
  
- **git push:** Envía los cambios locales al repositorio remoto.

- **git fetch:** Descarga los cambios del repositorio remoto al repositorio local, pero no los aplica.

- **git merge:** Combina los cambios de una rama con otra.

- **git pull:** Descarga los cambios del repositorio remoto y los aplica al repositorio local.

### Otros comandos útiles:

- **git commit -a:** Agrega archivos modificados al repositorio local sin pasar por el área de staging.

- **git branch:** Lista las ramas existentes o crea una nueva rama.

- **git remote:** Muestra los repositorios remotos configurados.

- **git tag:** Crea, lista y borra etiquetas.

- **git config:** Configura opciones de git.

### GitFlow:

Es una metodología para el manejo de ramas en proyectos de desarrollo, estableciendo estándares para la creación y gestión de ramas, nombres de ramas, y otros aspectos importantes.

### Recursos colaborativos:

- **git shortlog:** Muestra un resumen de commits por autor.

- **git blame:** Muestra quién modificó cada línea de un archivo y cuándo.

### Otros:

- **git rebase:** Reescribe la historia del repositorio.
  
- **git stash:** Guarda temporalmente cambios no deseados.
  
- **git clean:** Elimina archivos no deseados del repositorio.
  
- **git cherry-pick:** Trae un commit de otra rama a la rama actual.
  
- **git reflog:** Registra cambios en el repositorio incluso después de realizar un reset.

- **git grep:** Busca patrones en archivos del repositorio.

- **gitk:** Interfaz gráfica para visualizar la historia del proyecto.

---
