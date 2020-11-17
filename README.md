git init

git status
touch add 
git commit -m "Ajout d'un fichier"

git clone (lien)

git push //Poush vers github


git branch "NomDeLaBranche"

git checkout Branche

git commit -m nomDuFichier

git push -u origin master/

Choisir une branche : git checkout NomDeLaBranche

Fousionner une branche : git merge NomDeLa Branche en Restant sur master


// delete branch locally
git branch -d localBranchName

// delete branch remotely
git push origin --delete remoteBranchName


-----------------------------------------------------------------------------
-Commandes de base
Créer le repertoire
git init
git status

	//Charger les fichiers en ligne:
	git add fileName 	      // Choisir les fichiers à mettre en ligne
	git commit -m "first commit" // Deuxième étape pour charger les fichiers

	//Charger les fichiers modifiés exemple de index.php
	git add index.php
	git commit -m "Chargement du fichier modifié"

	git log // historiques de toutes les modifications

//BRANCH
git branch  // lister les branches disponibles

git branch bgcolor

 git checkout NomDeLaBranche //Choisir une branche

 git merge NomDeLa Branche en Restant sur master //Fousionner une branche

 git branch -d bgcolor //Supprimer une branche

git remote add origin https://github.com/marc2015/01.git

git push -u origin master //Envoyer en ligne

git pull origin master  //Récupérer le projet

git push origin master -f


this work for me

git init

git add --all

git commit -m "name"

git push origin master --force


//SUPPRIMER FILES

git rm file1.txt
git commit -m "remove file1.txt"
git push origin branch_name 



git config --global core.excludesfile ~/.gitignore


GITIGNORE
touch .gitignore
git rm --cached FILENAME
git config --global core.excludesfile ~/.gitignore

CHANGE BRANCHE
git remote -v
/list

 git remote set-url origin https://github.com/USERNAME/REPOSITORY.git
 
 git remote -v
 
 git checkout .

//Création d'une autre branche

git checkout -b "nomDeLaNouvelleBranche" "origin/master"

git checkout -b myFeature dev //Create a new branch from dev branch

git branch

//Fusion de deux branches
git checkout brancheA
git merge brancheB

git branch -a
# *master
#  test
#  remote/origin/master
#  remote/origin/test

git branch -d test
# Deleted branch test (was ########)

git pull

git remote rm origin

git reverse


// delete branch locally
git branch -d localBranchName

// delete branch remotely
git push origin --delete remoteBranchName

//Then run the following commands from the top folder of your Git repository:
 ```bash
git rm -r --cached .
git add .
git commit -m "fixed untracked files"
git git push -u origin master
 ```
## TAGS

Web site : https://git-scm.com/book/en/v2/Git-Basics-Tagging
## Create tags

### git show v1.4
## Tags annotés
#### git tag -a v1.4 -m "my version 1.4"

## Tags légers
#### git tag v1.4-lw 

## Répertorier les tags
#### git tag 
####  git tag -l *-rc*

## Taguer de nouveau/Remplacer d'anciens tags
### git tag -a -f v1.4

## Partage : faire un push de tags vers un dépôt distant
### git push origin v1.4

## Faire un check-out de tags
### git checkout v1.4

## Supprimer des tags
#### git tag -d v1 $ git tag v2 v3 
#### git tag v1.4-lw 


