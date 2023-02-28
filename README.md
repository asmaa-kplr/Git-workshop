# Git & GitHub Workshop

Dans cet atelier, nous allons vous guider à travers des étapes pour utiliser Git et Github. Nous allons vous montrer comment créer un nouveau dépôt Git, ajouter des
fichiers à ce dépôt, créer des commits pour enregistrer les modifications, créer un nouveau dépôt Github, ajouter le dépôt local au dépôt Github et pousser les modifications vers le dépôt Github.

# 1 . Configuration de Git
Ouvrez l'invite de commande sur votre ordinateur et tapez les commandes suivantes pour configurer votre nom d'utilisateur et votre adresse e-mail :
```
git config --global user.name "Votre nom d'utilisateur"
git config --global user.email "Votre adresse e-mail"
```
# 2 . Création d'un nouveau dépôt Git
Pour créer un nouveau dépôt Git, ouvrez l'invite de commande et naviguez vers le dossier où vous souhaitez créer votre dépôt. Tapez la commande suivante pour initialiser un nouveau dépôt Git :
```
git init
```
# 3 . Ajout de fichiers au dépôt Git
Maintenant que vous avez initialisé votre dépôt Git, vous pouvez y ajouter des fichiers. Copiez les fichiers que vous souhaitez ajouter dans le dossier du dépôt, puis tapez la commande suivante pour les ajouter :
```
git add <nom-fichier>
```
Cette commande ajoute tous les fichiers du dossier au dépôt.

# 4 . Création d'un commit 
Une fois que vous avez ajouté des fichiers au dépôt, vous devez créer un commit pour enregistrer les modifications. Tapez la commande suivante pour créer un commit :
```
git commit -m "Votre message de commit"
```
Remplacez "Votre message de commit" par un message décrivant les modifications apportées aux fichiers.

# 5 . Pousser les modifications vers le dépôt Github

Enfin, vous pouvez pousser vos modifications vers le dépôt Github en tapant la commande suivante : 
```
git push -u origin master
```
Cette commande pousse les modifications du dépôt local vers le dépôt Github.
