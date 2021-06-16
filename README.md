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


