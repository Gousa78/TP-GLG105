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
- Créer un fichier "MonFichier.txt"
- Vérifier le résultat
- Prise en compte du fichier créé dans le repository
- Vérifier le résultat
- Créer un fichier "error.log" contenant "Error processing"
- Mettre en place un méchanisme afin de ne pas prendre en compte dans le repository le fichier "error.log"
  - **Remarque** : Ce méchanisme devrait être inclus dans le repository

## TD2
- Faire un premier commit
- Vérifier le résultat
- Relever les 6 1er chiffres du SHA-1 et enregistrez les dans un fichier "histo.txt" que vous ajoutez au
dépôt
- Modifier le fichier "MonFichier.txt"
- Visualiser les modifications effectuées dans "MonFichier.txt" et enregistrez les dans un fichier "diff.txt" que vous ajoutez au
dépôt
> Sous un shell linux vous pouvez utiliser > pour que la sortie standard soit redirigée sur un
fichier.
> Par exemple ls -l > liste.txt écrit la liste des fichiers du répertoire courant dans le fichier
liste.txt.
- Committer ces deux fichiers

## TD3
- Pousser ensuite les commits effectués sur le dépôt distant
- Donner une version au dépôt local
- Afficher la description de l'étiquette créée
- Mettre à jour le dépôt distant
