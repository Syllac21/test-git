modif branch-b
modif branch-a

Exercice GIT base manip 

1/ créer un dossier de projet mkdir test-git

2/ créer 3 dossiers (html/css/js) 
	mkdir html 
	mkdir css 
	mkdir js

3/ créer les fichiers index.html, index.js et styles.css dans leurs dossiers respectifs 
	touch index.html 
	touch index.js 
	touch styles.css

4/ mettre a jour l'ensemble dans le dossier remote 
	git init 
	git branch -M main 
	git remote add origin https://github.com/Syllac21/test-git.git git 
	add * git 
	commit -m "first commit" 
	git push origin main

5/ créer une branche "dev"
	git branch dev

6/ lister les branches
	git branch

7/ se positionner sur la branche dev
	git checkout dev

8/ modifier le fichier css 

9/ mettre la modif a jour sur la branche dev
	git add *
	git commit -m "text color"

10/ revenir sur la branche master et ouvrir le fichier css (voit-on la modif ?) 
	non

11/ fusionner la branche dev sur la branche master 
	git checkout main
	git merge dev

12/ verifier la modif css

13/ retourner sur la branche dev et ajouter un fichier readme.md
	git checkout dev

14/ faire un commit de ce fichier 
	git commit -a -m "readme.md"

15/ visualiser les differences avec la commande adéquate : 
	git diff main

16/ créer deux nouvelles branches branch-a et branch-b
	git branch-a
	git branch-b

17/  dans chaque fichier readme de chaque branche, ajoutez une ligne spécifique (modif branch-a et branch-b par ex)

18/ comparez les deux branches avec la fonction adéquate 
	git diff branch-a
ça bloque ici

19/ mergez la branche a sur master 

20/ mergez la branche b sur master 

21/ essayez de resoudre le conflit ... ok


