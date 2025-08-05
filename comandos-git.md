- git status: Muestra el estado del directorio
- git log: Muestra el historial de commits de un repositorio
- git pull: Realiza dos acciones -> git fetch (descarga los cambios) y git merge (los fusiona con tu código actual)
- git add: Agregar archivos modificados o nuevos al área de preparación
- git commit -m "mensaje": Guarda los cambios realizados en un proyecto como una nueva versión, creando un "punto de guardado" en el historial del proyecto.
- git push: Se utiliza para enviar los cambios realizados en un repositorio local a un repositorio remoto
- git diff archivo: Muestra los cambios del archivo
- git restore --source numerodeHash nombreArchivo: Restaura un archivo a la version del hash EJ: git restore --source de142d7 index.html
- git branch: Muestra las ramas del proyecto
- git checkout: Sirve para cambiar entre ramas y restaurar archivos del directorio de trabajo
- git checkout -b nombreRama: Para crear una rama
- git checkout nombreRama: Para cambiar entre ramas
- git switch nombreRama: Se utiliza para cambiar entre diferentes ramas de un repositorio
- git push origin nombreDeLaRama: Para hacer push desde una rama
## Pasos para un merge
1. git merge nombreDeLaRama: Para unir la rama en la que estas con la nombrada. EJ: git merge desarrollo, desde la rama main
2. git push origin main: Para hacer push desde main despues de hacer merge
## Creacion de nuevo repositorio
1. git init: Crea un nuevo repositorio Git vacío en el directorio actual.
2. Seguir los pasos de Github. 
    * EJ: git remote add origin https://github.com/Marcelo99upsa/sistema-de-registro-2.git<-Esto es el repositorio vacio en Github
    * git branch -M main
	* Esto podria necesitarse antes de la siguiente linea de codigo: git pull origin main
    * git push -u origin main