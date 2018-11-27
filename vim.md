
![logovim](image/vim.png)


=LES COMMANDES DE VIM=
---------------------------------


`k` 	↑ 	Se déplacer vers le haut  
`j` 	↓ 	Se déplacer vers le bas  
`h` 	← 	Se déplacer vers la gauche  
`l` 	→ 	Se déplacer vers la droite  


 =LES SELECTIONS=  
----------------------------------  


`aw`     		Un mot  
`as` 	    	Une phrase (sentence)  
`ap` 		    Un paragraphe  
`a(, a[, a<, a{`Un bloc délimité  
`a", a', a` 	Un bloc encadré de guillemets  
`at` 		    Une balise (tag) à la XML  


 =LES MOUVEMENTS=  
---------------------------------------  

`$` 		Aller en fin de ligne  
`0` 		Aller en début de ligne  
`^` 		Aller au premier caractère qui n'est pas un espace ou une tab de la ligne  
`gg` 		Aller en début de document  
`G` 		Aller en fin de document  
`:<n>` 		Aller à la ligne <n> (où <n> est un nombre entier)  
`f<s>` 		Jusqu'au caractère <s> en allant vers l'avant  
`F<s>` 		Jusqu'au caractère <s> en allant vers l'arrière  
`t<s>` 		Jusqu'au caractère <s> en allant vers l'avant et en s'arrêtant juste avant  
`T<s>` 		Jusqu'au caractère <s> en allant vers l'arrière et en s'arrêtant juste avant  


 =LES INTERVALLES=
--------------------------------------------


`<n>` 		       La ligne n
`.` 		       La ligne courante
`%` 		       Toutes les lignes du fichier
`/<motif>/`        La prochaine ligne vérifiant le motif  
`$` 		       Dernière ligne  
`<spec1>,<spec2>`  De la spécification de ligne 1 à la spécification de ligne 2  


 =LES MODES=  
----------------------------------------------  


`i` 		       Entre en mode insertion au niveau du curseur    
`a 	li` 	       Entre en mode insertion après le curseur    
`A 	$a` 	       Entre en mode insertion sur le dernier caractère  
`o 	A<Entrée>` 	   Insère une ligne vide sous le curseur, place le curseur sur cette ligne, et entre en mode édition  
`O` 		       Idem mais une ligne au dessus du curseur  
`v` 		       Entre en mode visuel  
`V` 		       Entre en mode visuel par ligne  
`<C-v>` 		   Entre en mode visuel par bloc  
`R` 		       Entre en mode remplacement  
`<Echap> 	<C-c>` Entre en mode normal  
`:` 		       Entre en mode commande (vous devez être en mode normal)  
`<C-o>` 		   En mode insertion, retourne en mode normal pour une seule commande, puis retourne en mode insertion juste après  
 

 =SUPPRESION=  
-----------------------------------------------  


`x` 		Le caractère sous le curseur  
`s` 		Comme x mais entre en mode insertion après  
`dd` 		La ligne sous le curseur  
`dw` 		Le mot sous le curseur  
`d$ 	D` 	Supprime jusqu'à la fin de la ligne  
`d<mouvement>` 		Du curseur à la cible du déplacement  
`d<sélection>` 		La sélection précisée  
`c` 		Se comporte comme d mais entre en mode insertion après la suppression  
`u` 		Annulation de la dernière action  
`CTRL+R` 		Remettre (annuler l'annulation)  


 =COPIER=  
-------------------------------------------------  


`yy 	Y`      	Copie une ligne  
`yw` 		        Copie un mot  
`y$` 		        Copie du curseur à la fin de la ligne  
`ygg` 		        Copie du curseur au début du document  
`y<mouvement>` 		Copier jusqu'à la cible du mouvement  
`y<sélection>` 		Copier la sélection précisée  
`p`  		        Coller  


 =SAUVEGARDE=  
----------------------------------------------------  


`:w` 		        Sauvegarder  
`:q` 		        Quitter  
`:q!` 		        Quitter sans enregistrer  
`:wq 	:x` 	    Quitter et enregistrer  
`:saveas` 		    Enregistre désormais le fichier sous ce nom  
`:up 	:update` 	Enregistre le buffer courant si il a été modifié  


 =POUR LES CODEURS=  
------------------------------------------------------  


`==` 		    Réindente la ligne sous le curseur  
`gg=G` 		    Réindente tout le document  
`=i{ 	=a{` 	Réindente tout le bloc courant, accolades exclues (inner-bloc) ou inclues (a)  
`K` 		    Va essayer de trouver la documentation correspondant au mot sous le curseur  



