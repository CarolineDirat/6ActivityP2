Voici les comandes Git appelées dans le terminal (la console) pour créer le repository Git 6ActivityP2 et son premier fichier README.txt

-- -----------------------------------------------------------------------------------------------------------------------------
cd FormationGit			-- Je me place dans le dossier qui contiendra mon repository
mkdir 6ActivityP2		-- Création du dossier 6ActivityP2
cd 6ActivityP2			-- et je m'y place dedans
git init				-- pour pouvoir l'activer comme repository Git

touch README.txt 		-- je crée le fichier README.txt
git add README.txt 		-- je l'ajoute à l'index des fichiers suivis par Git

git commit -m "Ajout du fichier vide README.txt"	-- je commite l'ajout du fichier README.txt dans le repository 6ActivityP2

-- -----------------------------------------------------------------------------------------------------------------------------

Ensuite, dans mon éditeur de texte Sublime Text, j'écris le contenu du fichier README.txt qui présente le projet, c'est-à-dire qu'il contient les consignes à suivre pour réaliser l'activité.

J'enregistre les modifications.

-- -----------------------------------------------------------------------------------------------------------------------------

-- Et enfin, je commite la modification du contenu du fichier README.txt (dèjà présent dans l'index, donc l'option -a me permet de le faire en une seule ligne de code au lieu de "git add" suivi de "git commit") :

git commit -am "Modification du fichier README.txt pour présenter le projet (l'activité)"		

-- -----------------------------------------------------------------------------------------------------------------------------

REMARQUE :

Régulièrement, on peut utiliser :
	- la commande "git status" pour voir où en est le status de Git
	- la commande "git log" pour voir l'historique des commits du repository