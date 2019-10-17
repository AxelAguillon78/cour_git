Deuxieme états : 

Git --no-pager log --oneline : 
Permet d'afficher le nombre maximum de commit

Git --no-pager log (-chiffre) --oneline : 
Permet d'afficher les dernier commit

git log --author : 
Permet de voir les commit d'un auteur en particulier

git log --before =(date) : 
Permer de voir les a cette date 

Git diff  (--cached)
Permet de voir les difference d'un qui n'a était add 
[--cached] Permet d'afficher les différences entre le dernier commit et l’index


Git diff HEAD~(chiffre) : 
Permet de voir les difference des different commit d'avant 

Git diff --stat : 
Permet les difference en + ou - 

Git restore : 
Permet de remettre le fichier non index a lorigne avant les modif

Git restore --staged : 
Permet de remettre le fichier index a lorigne avant les modif

Git reset HEAD~1 :
Permet Annule le dernier commit et met tout dans le working Directory sans perte 

git reset --soft HEAD~1 : 
Permet d'annule le dernier commit et met tout dans la staging area sans perte

git reset --hard HEAD~1 : 
Permet d'annule le dernier commit et supprime les modifications...(danger)

mkdir : 
Permet de crée un dossier 

cd : 
Permet de changer de dossier 

git revert :
Permet de crée un commit qui annule les changement des commit donné



