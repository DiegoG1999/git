# Clase 02 - Git desarrollo colaborativo

## Repasando dinamica de trabajo base de git


### Haciendo un commit. Pasos


1 hacer un status para ver en que estado estan los archivos que quiero sean parte del commit

2 Agregar lo que quiero dentro del commmit al área de confirmación (stating area)

git add <nombre-archivo>
git add clase02/readme.md
git add # agregar todo lo que sea parate de la funcionalidad en la que trabajo

3. Hago el commit. Todo lo que estuviera en el area de stating se guarda en el repositorio local

git commit -m "nuevo commit, mensaje descriptivo"

## git diff comparo entre diferentes commits en el tiempo

git diff <hash> <hash>
git diff 6ceff27 376047e

