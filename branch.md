Troisieme Partie : 

git branch (dev) : 
Permet de crée la branch
[dev] Permet de crée la branche dev

git checkout (dev) : 
Permet de ce deplacer dans la branch 
[dev] Permet de ce deplacer dans la branche dev 
 
git branch -d : 
Permet de supprimer la branch

git merge : 
Permet de reunir des branch

git merge --no-ff : 
Permet de reunir des branch meme si elles ont le meme contenue 

git branch --no-merged : 
Permet de lister toutes les branches non mergées

git log --oneline --graph :
Permet de visualiser le graph des commit à partir de la branche master

git stash : 
Permet de crée une stash de commit dans fichier .sh

git stash list : 
Permet de lister ce qui est dans le stash 

git stash apply : 
Permet de recupérer ce qui est dans stash

git stash drop : 
Permet de retirer se qu'il y avais dans stash 

git stash apply --index : 
Permet remettre ce qui était dans l'index

git stash list : 
permet de recuperer une partier des commit en particulier 

sh : 
cree un fichier stash

git tag : 
Permet de lister les tag 

git tag [-a] [-m] : 
(-a)
(-m) Permet de rajouter une déscription

git tag -l 
Permet de rechercher des tags particuliers

git show : 
Permet de voir un tag annoté

git --bare init : 
Permet de création du server Git

git remote add origin (C:...) : 
Permet de dire le chemin absolue du serveur 

git push origin master : 
Permet d'envoyer les branch manster dans le serveur disantent

git pull origin master : 
Permet de reçevoir se quil y a dans la branch master du serveur disantent

git remote : 
Permet de lister les dépôts distants

git remote add [alias] [chemin_du_serveur_distant] : 
Permet ajouter un dépôt distant

git remote rm ou rename : 
Permet de supprimer ou renommer un dépôt distant

git fetch origin : 
Permet récupérer la branche distante

git log master..origin/master : 
permet de comparer les différences entre master

git remote show origin : 
Permet d'inspecter un dépôt distant




