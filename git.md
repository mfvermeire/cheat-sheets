![logo_git](image/git.png)


=Premier pas sur GIT=  
----------------------  


Pour vérifier si on a installé Git dans le Terminal, tapez : git –version  


   *Créer un nouveau projet et initialiser Git*  
    --------------------------------------------  

- Créer un nouveau dossier  


	mkdir nomdudossier  
	cd nomdudossier  
	git init  
	git status  


   *Ouvrir le dossier et créer une nouveau fichier, puis ajouter un peu de contenu :*   
    ----------------------------------------------------------------------------------  


 - Créer un nouveau ficher  


	touch nomdufichier  
	ls -lh (pour voir les fichier et les droits) *optionnel  
	git status  
	git add nomdufichier  
	git status  
	git commit -m « Nommez les changements apportés » (ne pas oublier les « . »!)  
	git status  


 - Faire des changements dans le fichier puis faire un git status. Un message du style « Modifications qui ne seront pas validées : » va apparaître.   


	git diff (indication sur les changement apportés)  
	git add nomdufichier  
	git commit –m « modification apportés » (ne pas oublier les « . »)    
	git status   

Un message du style « rien à valider, la copie de travail est propre » va apparaître.     

Pour voir les différentes modifications apportés, son auteur, la date et le nom de la branche, tapez :* git log*  

