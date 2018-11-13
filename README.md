
# Commandes GIT

![Logo Git](https://www.lije-creative.com/wp-content/uploads/2013/09/git-ligne-commande.png.pagespeed.ce.LbKXCliCua.png)
## Commandes de base

### Init
`git init`
> Première commande git, création du repository

### Config
`git config --global|local user.name|email name|email`
> Permet de paramétrer le repository.

### Add
`git add file_name`
> Ajout du fichier à suivre dans git (ajout dans l'index).

### Commit
`git commit -m "message"`
> Valide les modifications effectuées. Le message sert de note au commit.

### Status
`git status`
> Indique le status du repository et des fichiers.

### Log
`git log`
> Affiche l'historique des commits.

### Tag
`git tag -a v1.0.0 -m "My version 1.0.0"`
> Création d'un tag


## Commandes avancées

### Branch
`git branch branch_name`
> Créer une branche.
> **La bonne pratique est de ne pas développer directement sur la branche master mais de créer une branche pour chaque features.**

### Checkout
`git checkout commit_number|branch_name`
> Permet de revenir à un commit précédent ou de changer de branche.
> **Il est important de vérifier sur quelle branche nous nous situons.**

### Reset
`git reset file_name`
> Supprime le fichier de l'index.

### Revert
`git revert commit_num`
> Annule les modifications apportées par le commit concernées

### Merge
`git merge branch_name`
> Jointure d'une branche sur la branche courante.

### Rebase
`git rebase branch_name`
> Fait passer les commits effectuées sur une branche sur la branche courante. Permet d'éclaircir l'historique.
![enter image description here](https://cdn-images-1.medium.com/max/2000/1*FNaZp740nmp8wz851BqcAg.png)

### Log decorate
`git log --decorate --graph`
> Affiche le graph des commits.

### Stash
`git stash`
> Permet de mettre en pause (équivalent à un commit local).

### Stash apply|pop
`git stash apply|pop`
> Permet de revenir du stash en le gardant|supprimant.

## Commandes pour GitHub

### Remote
`git remote add origin address_repository_github`
> Ajoute le dossier git courant au serveur distant sur le repository indiqué. Le nom "origin" peut-être remplacé par ce que l'on veut.

### Push branch
`git push -u origin branch_name`
> Envoie la branche indiquée sur le serveur distant

### Push
`git push`
> Après avoir indiqué la branche précédemment,  permet d'appliquer les commits sur le serveur distant.

### Clone
`git clone address_repository`
> Récupère le repository indiqué dans le dossier courant.

### Fetch
`git fetch <REMOTE>`
> Consulter les changements survenus sur le REMOTE


### tououtoutou
