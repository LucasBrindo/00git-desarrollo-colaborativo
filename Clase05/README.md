Clase 05
git status
git add .
git commit -m "mensaje descriptivo"
git push
git status
git fetch



# Git Reset

git reset --soft

git reset --mixed

git reset --hard

## -----------------------------
git switch -c 'rama resets'
 git log online             veo si esta la rama
git add . && git commit -m"agrego titulo reset soft"   hace las dos cosas al mismo tiempo
git add . && git commit -m"agrego definicion de reset soft"   

git reset --soft <hash>

git add . && git commit -m "agrego comando reset soft"   


git add . && git commit -m "agrego titulo reset mixed" 

## es el reset por defecto, agarra los comit que les diga y los borra, dejando el contenido de los commit dentro del working directory WD

git add . && git commit -m"agrego descripcion reset mixed" 

git reset <hash> ó
git reset --mixed <hash>
git add . && git commit -m "agrego funcion reset mixed" 

git add . && git commit -m "agrego titulo reset hard" 
agarra los commit y el contenido los descarta

git add . && git commit -m"agrego descripcion reset hard"

git add . && git commit -m "agrego funcion reset hard" 

git reset --hard <hash>


