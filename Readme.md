# Git verziókezelés

## Helyi repo létrehozása

- helyi repo inicializálása
	> git init
 - felhasználónév és e-mail cím ellenőrcése
 > git config user.name
 > git config user.email
- ellenőrzés
	> git status
- előkészítjük a commit-ra (a verzió létrehozására)
	> git add .
- ellenőrzés:
	>git status
- commit:
	> git commit -m "first commit"
- a commit-ok listázása
	> git log
## helyi repo összekapcsolása a távoli repo-val

- távoli repo létrehozása
- a helyi repo összekapcsolása a távolival
	> git remote add origin https://token@github.com/hanakkristof/grid.git
- legelső alkalommal a push:
	> git push -u origin master
- a továbbiakban:
	> git push
