# TP GIT

## Installation

Installation sous Windows   https://git-scm.com/download/
 
Vérification de l’installation

`$` `git --version`


Mise à jour version git

`$`  `update-git-for-windows`


Aide en ligne

`$`  `git –help`

`$`  `git help git`


## Configuration

`$` `git config --global user.name "VotreNom"`

`$` `git config --global user.email VotreAdresse@mail.com`

### Visualisation de la configuration 
- Global - Spécifique à l'utilisateur, stockée à la racine de son compte, dans le fichier `~/.gitconfig`

`$`  `cat "C:\Users\rocheteau\.gitconfig"`

- Local - Spécifique à chaque dépôt local, stockée dans le fichier `.git/config`


- Système - Généralement stockée dans `/etc/gitconfig`, partagée par tous les utilisateurs

`$`  `Cat "C:\Program Files\git\etc\gitconfig" `

### Alias
`$`  `git config --global alias.co checkout`

`$`  `git config --global alias.ci commit`

`$`  `git config --global alias.st status`

### Visualisation des alias
`$`  `git st`