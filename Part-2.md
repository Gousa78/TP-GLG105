# TP GIT

## TD1

### Repository création
************************

Création du repository

`$` `mkdir MonDepot`

`$` `cd MonDepot`

`$` `git int`
 
Visualisation du dépôt

`$` `git status`

Création d'un fichier MonFichier.txt

`$`  `touch MonFichier.txt`

Visualisation du dépôt

`$` `git status`

Ajout du fichier zone staging

`$` `git add MonFichier.txt`

Commit du code

`$` `git commit -m "Mon 1er commit"`

Exclusion de fichiers
- création fichier `error.log`

    `$` `touch error.log`
- Ajout code

    `$` `echo "error processing" >> error.log`
- 
- Création fichier exclusion

    `$`  `touch .gitignore`

- Ajout code

    `$` `echo "*.log" >> error.log`

Ajout des fichiers zone staging

`$` `git add MonFichier.txt, .gitignore`

Commit du code

`$` `git commit -m "Ajout fichier git ignore"`