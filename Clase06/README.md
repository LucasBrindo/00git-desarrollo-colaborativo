# Clase 06 - Git desarrolo colaborativo

## Git Alias --------------------------------------------------------
```sh
git config --global alias.l "log --oneline"

git config --global alias.ll "log --oneline --decorate --all --graph"
```
# despues solo ejecuto git l o git ll
```sh
git config --global alias.c "commit -m" ## git c "mensaje"

git config --global alias.s "status --short" ## git s

git config --global -e   ---->>>> para editar
```
## eliminar un alias: 
```sh
    git config --global --unset alias.<nombre del alias>
```
## ver la configuracion globarl del git:
```sh
git config --global --list


git config --global --get-regexp s 
```

## Distintos ambitos (scopes) ---------------------------------------
1. --system --> (nivel mas alto) todo el sistema operativo, usuarios y reposistorios
2. --global --> aplica a todos los repositoirios del usuario local, estandar
3. --local  --> (mas bajo) aplica al repositorio especifico en el que estoy trabajando

## git config --<scope> + el comadno que quiero usar

git config --system
git config --global
git config --local


