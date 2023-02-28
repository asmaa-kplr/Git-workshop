# Git & GitHub Workshop 1

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
Pour ajouter des fichiers à votre dépôt Git, vous pouvez utiliser la commande suivante :
```
git add <nom-fichier>
```
Ou vous pouvez ajouter tous les fichiers en une seule fois en utilisant :
```
git add .
```

# 4 . Création d'un commit 
Une fois que vous avez ajouté des fichiers au dépôt, vous devez créer un commit pour enregistrer les modifications. Tapez la commande suivante pour créer un commit :
```
git commit -m "Votre message de commit"
```
Remplacez "Votre message de commit" par un message décrivant les modifications apportées aux fichiers.

# 5 . Créer un dépôt sur GitHub 
Maintenant, vous pouvez créer un dépôt sur GitHub en vous connectant à votre compte et en cliquant sur le bouton "Nouveau dépôt". Donnez un nom à votre dépôt et cliquez sur "Créer le dépôt".


![image](https://user-images.githubusercontent.com/123757632/221890517-b9793939-b1a1-407b-96b4-0f3207dc9c93.png)

# 6 . Ajouter un dépôt distant 
Pour relier votre dépôt local à votre dépôt GitHub, vous pouvez utiliser la commande suivante :
```
git remote add origin url_du_dépôt_github
```
Remplacez "url_du_dépôt_github" par l'URL de votre dépôt GitHub.

# 7 . Pousser les modifications vers le dépôt Github

Enfin, vous pouvez pousser vos modifications vers le dépôt Github en tapant la commande suivante : 
```
git push -u origin nom_de_la_branche
```
Cette commande pousse les modifications du dépôt local vers le dépôt Github.
Remplacez "nom_de_la_branche" par le nom de la branche que vous souhaitez pousser.

