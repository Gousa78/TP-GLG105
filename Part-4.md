# TP GIT

## TD4

### Les branches
************************

Création branche `dev`

`$` `git branch dev`

Visualisation des branches

`$` `git branch`

Positionnement sur la branche `dev`

`$` `git checkout dev`

Visualisation

`$` `git branch`

Vérification de l'historique

`$` `git log`

Création du fichier `glg105.txt`

1. `$` `touch glg105.txt`
2. `$` `git add glg105.txt`
3. `$` `git status`
4. `$` `git commit -m "Ajout fichier glg105.txt"

Positionnement sur la branche `master`

`$` `git checkout master`

## TD5 & 6

### Les tags & merge
************************

Création d'une version

1. `$` `git tag --list`
2. `$` `git tag v1.0.0 IdenCommit`
3. `$` `git tag -- list`

Merge branche et suppression
1. `$` `git merge dev`
2. `$` `git branch -d dev`

## TD7

### Les fichiers
************************
1. `$` `git ls-tree HEAD`
2. `$` `git cat-file -p ÌdenBlob`

