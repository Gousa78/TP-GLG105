# TP GIT

## TD2

### Modification du repository
************************

Modification du fichier `MonFichier.txt`

Visualisation des modifications

`$` `git diff`

Création d'un fichier `diff.txt`

`$` `git diff >> diff.txt`

Visualisation du dépôt

`$` `git status`

Ajour des fichiers dans staging

`$`  `git add .`

Visualisation du dépôt

`$` `git status`

Visualisation des modifications

`$` `git diff --cached`


Commit du code

`$` `git commit -m "Ajout fichier historique et modification de MonFichier"`

## TD3
************************
### Modification staging

Création du fichier `test.tx`

Ajout au staging

`$` `git add test.tx`

Correction du nom du fichier `test.tx` => `test.txt`
1. `$` `git reset test.tx`
   1. `$` `mv test.tx test.txt`
2. `$` `mv test.tx test.txt`
