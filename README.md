# Todo sobre mi Git

* Git pull origin main: baja los cambios que están en el remoto de main y los mergea contra mi copia local

* pwd: muestra la ruta en la que estoy

* git clone > Clonar repo

* git branch -a > Mostrar las ramas del repo local y remotas, para salir escribir q

* git branch > Comprueba y Muestra en que rama local estoy

* Git branch nombre_rama > creo rama

* git checkout -b nombrerama > Crear rama local con nombre

* git checkout > Cambiar de rama

* git log > muestra el historial de cambios, para salir ingresar la letra q

* git add . > agrega todos los archivos que han sido modificados

* Git add nombre_archivo > agrega los cambios en ese archivo

* git commit -m “msj del commit” > hacer un commit

* git push > publica la rama local en el repositorio remoto, también puedo subir solo cambios y actualizar lo que este en el remoto.

* git push origin nombre_de_mi_rama_local > lleva la rama local al remoto.

* git push --set-upstream origin nombre_rama > se enlaza la rama local con la rama remota que esta en GITHUB. Delimito la rama en donde voy a hacer los cambios 

* Git pull > traer actualizaciones realizadas por otras personas

* git clone --single-branch --branch <branchname> <remote-repo>

* git merge <nombre de la rama de prueba> <nombre de la rama creada> copia todo lo de una rama a otra

* pull request > es la acción de validar un código que se va a mergear de una rama a otra. 

* git push origin --delete nombre_rama_remota > elimina rama remota

* git branch -d nombre_rama_local > elimina rama local

* ls -la: muestra si dentro de cada repo tengo el archivo .git

*  git restore . > restaura el repo como estaba
  
* git merge main > trae cambios desde el main


————————————
Creamos rama:  git checkout -b nombre_rama
Pararse en la rama que creamos: git checkout
Copiar lo de máster: git pull origin test_1/master/main

- git status: para verificar si hay archivos en color rojo(sin seguimiento)
- git add . :  (Agrego los archivos al seguimiento)
- git status: los archivos van a estar en verde
- git commit -m “tex” (associate cambios a un mensaje)
- git pull origin nombre_rama_remota (evita pausar cambios de los demás)
- git push origin natalia_1: Sube los cambios comiteados de la rama local a la remota.
  
  
  
  
# Como resolver conflictos

Cuando trabajamos con repositorios colaborativos varios usuarios podrían estar editando un mismo archivo o contenido en ramas separadas.

Los conflictos surgen cuando dos personas han cambiado las mismas líneas de un archivo o si alguien ha eliminado un archivo mientras otro lo estaba modificando.

La función principal de **git merge** es combinar ramas separadas y resolver las ediciones conflictivas que podrían surgir.

Al realizar el git merge pueden detectarse conflictos que se deben resolver. Los conflictos solo afectan al desarrollador que realiza la fusión, el resto del equipo no se entera del conflicto.

1. Ejemplo de conflicto
## Paso 1

- Crea un nuevo proyecto en Pycharm e inicializarlo como repositorio git.

- Crear un nuevo archivo merge.txt con texto.

- Realizar el git add . y git commit de los cambios.


## Paso 2

- Crear nueva rama (rama_1)

- Modificar el texto del archivo merge.txt.

- Confirma el nuevo contenido (git add . + git commit)
  

## Paso 3

- Volver a master

- Editar contenido en merge.txt

- Confirmarlo (git add . + git commit)


 ## Paso 4

- Posicionarse en master (git checkout master)

- Hacer el merge de la rama creada (git merge rama_1).
  
  
  
### Cuando trabajamos con repositorios remotos: 

Si estamos trabajando en una rama propia, antes de hacer un PR para megear a main/master, se recomienda traer los cambios git pull origin main y resolver los conflictos de forma local.  


