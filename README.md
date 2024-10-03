# TODO ACERCA DE LA PROGRAMACIÓN 


## Temas a tratar 
- [HTML]
- [CSS]
- [JAVASCRIPT]
- [jQuery]
- [NODE]
- GITHUB
- [REACT]
- DATA BASE ([MYSQL] - [ORACLE] - [POSTGRESQL] - [MONGODB] )
-------------------------------------------------------------

---------------------------
### 🛠EJERCICIOS PARA FRONT-END
- https://exercism.org/tracks/javascript/exercises/lasagna
- https://leetcode.com/studyplan/30-days-of-javascript/


### 🛠 EJERCICIOS PARA BACK-END
- https://learnsql.es/blog/19-ejercicios-practicos-de-postgresql-con-soluciones-detalladas/
---------------------------

---------------------------
## Usage/GITHUB
Variaciones de Git Reset

- git reset --soft:
  Borra el historial y los registros de Git de commits anteriores, pero guarda los cambios en Staging para aplicar las últimas actualizaciones a un nuevo commit.
- git reset --hard:
  Deshace todo, absolutamente todo. Toda la información de los commits y del área de staging se elimina del historial.
- git reset --mixed:
  Borra todo, exactamente todo. Toda la información de los commits y del área de staging se elimina del historial.
- git reset HEAD:
  El comando git reset saca archivos del área de staging sin borrarlos ni realizar otras acciones. Esto impide que los últimos cambios en estos archivos se envíen al último commit. Podemos incluirlos de nuevo en staging con git add si cambiamos de opinión.

#### Git rm
Por otro lado, git rm es un comando que nos ayuda a eliminar archivos de Git sin eliminar su historial del sistema de versiones. Para recuperar el archivo eliminado, necesitamos retroceder en la historia del proyecto, recuperar el último commit y obtener la última confirmación antes de la eliminación del archivo.

Es importante tener en cuenta que git rm no puede usarse sin evaluarlo antes. Debemos usar uno de los flags siguientes para indicarle a Git cómo eliminar los archivos que ya no necesitamos en la última versión del proyecto.

#### Variaciones de Git rm
- git rm --cached: Elimina archivos del repositorio local y del área de staging, pero los mantiene en el disco duro. Deja de trackear el historial de cambios de estos archivos, por lo que quedan en estado untracked.
- git rm --force: Elimina los archivos de Git y del disco duro. Git guarda todo, por lo que podemos recuperar archivos eliminados si es necesario (empleando comandos avanzados).
- 
#### ¿Cuál es la diferencia entre git rm y git reset Head?
La diferencia principal entre git rm y git reset HEAD radica en que git rm elimina archivos del repositorio y de la historia del proyecto, mientras que git reset saca los cambios del área de preparación y los mueve del espacio de trabajo, sin afectar la historia del repositorio.

![Git rm](https://static.platzi.com/media/user_upload/git-reset%20%281%29-77a1294a-fb8b-43d0-aace-a517c1a05c2e.jpg)


#### ¿Cuándo utilizar git reset en lugar de git revert?
Para reescribir la historia del repositorio y eliminar confirmaciones anteriores, se utiliza git reset. Para deshacer cambios de confirmaciones anteriores de forma segura sin modificar la historia del repositorio, se emplea git revert.
![Git rm](https://static.platzi.com/media/user_upload/lifecycle-674998bf-5510-4dc9-9840-edcbe86bf1e8.jpg)


#### Resumen 
![Git rm]([https://static.platzi.com/media/user_upload/git-reset%20%281%29-77a1294a-fb8b-43d0-aace-a517c1a05c2e.jpg](https://static.platzi.com/media/user_upload/4-90f7d57a-0d77-4afa-b69e-e45966c52a37.jpg))

