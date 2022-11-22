# TP-GLG105 - Git notions de base
## Modalités
- Travail individuel et à effectuer sur Github Classroom

## Prérequis
- Installation de Git. Téléchargement ici : https://git-scm.com/downloads
- Configuration de Git. Association des commits aux noms et adresse e-mail
- Création d'un compte Github
- Enregistrement assignement Github Classroom : https://classroom.github.com/a/zSO6RjhJ

## TD1
- Créer un repository "MonDepot"
- Vérifier le résultat 
- Créer un fichier `MonFichier.txt`
- Vérifier le résultat
- Prise en compte du fichier créé dans le repository
- Vérifier le résultat
- Créer un fichier `error.log` contenant "Error processing"
- Mettre en place un méchanisme afin de ne pas prendre en compte dans le repository le fichier `error.log`
  - **Remarque** : Ce méchanisme devrait être inclus dans le repository

## TD2
- Relever les 6 1er chiffres du SHA-1 du 1er commit et enregistrez les dans un fichier `historique.txt` que vous ajoutez au dépôt
- Modifier le fichier `MonFichier.txt`
- Visualiser les modifications effectuées dans `MonFichier.txt`
  - Enregistrez les dans un fichier `diff.txt` en indiquant le numéro du TD et ajoutez au dépôt
    - ***Note:*** Sous un shell linux vous pouvez utiliser `>` pour que la sortie standard soit redirigée sur un fichier.
    - Par exemple `ls -l > liste.txt` écrit la liste des fichiers du répertoire courant dans le fichier liste.txt.
- Visualiser les modifications effectuées dans `MonFichier.txt`
  -  Comparer le résultat avec le contenu du fichier `diff.txt`
- Committer les fichiers
- Lancer GITK

## TD3
- Créer un fichier `test.tx`
- Ajouter le à la zone staging
- Corriger le nom du fichier par `test.txt` de deux manières différentes

## TD4
- Visualiser les modifications entre 1er commit et le dernier
  - Enregistrez les dans un fichier `historique.txt` en indiquant le numéro du TD4.1
- Visualiser les modifications du fichier `MonFichier.txt`
  - Enregistrez les dans un fichier `historique.txt` en indiquant le numéro du TD4.2
 - Ajouter au dépôt

## TD5
- Créer une branche nommée `dev`
- Visualiser les banches
  - Indiquer la branche sur laquelle vous vous trouvez
- Aller sur la branche `dev`
  - Visualisation du repository
- Créer un fichier `glg105.txt`
  - Ajouter le au repository
  - Retourner sur la branche `master`
  - Quelle est votre constat?
  
## TD6
- Donner une version au dépôt localh
- Afficher la description de l'étiquette créée
- Merger la branche `dev`avec la branche `master`
- Supprimer la branche `dev`
- Que constatez-vous?

## TD7
- Retouver le SHA1 du fichier `MonFichier.txt`
- Afficher son contenu en utilisant le SHA1 
