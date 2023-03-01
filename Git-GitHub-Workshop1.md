# Git & GitHub Workshop 1

Dans cet atelier, nous allons vous guider à travers des étapes pour utiliser Git et Github. Nous allons vous montrer comment créer un nouveau dépôt Git, ajouter des
fichiers à ce dépôt, créer des commits pour enregistrer les modifications, créer un nouveau dépôt Github, ajouter le dépôt local au dépôt Github et pousser les modifications vers le dépôt Github.


# 1 . Configuration de Git
Alice et Bob : Ouvrez l'invite de commande sur votre ordinateur et tapez les commandes suivantes pour configurer votre nom d'utilisateur et votre adresse e-mail :
```
git config --global user.name "Votre nom d'utilisateur"
git config --global user.email "Votre adresse e-mail"
```
# 2 . Création d'un nouveau dépôt Git
Pour créer un nouveau dépôt Git, Alice et Bob ouvrez l'invite de commande et naviguez vers le dossier où vous souhaitez créer votre dépôt. Tapez la commande suivante pour initialiser un nouveau dépôt Git :
```
git init
```

# 3 . Travailler sur un fichier dans le dépôt 

Créez un fichier texte "fichier.txt" en utilisant un éditeur de texte

Ajouter le fichier à la zone de staging.La zone de staging est une zone intermédiaire qui contient les modifications que vous souhaitez inclure dans votre prochain commit, vous pouvez utiliser la commande suivante :
```
git add <nom-fichier>
```
Pour valider les modifications et ajouter un message de commit qui décrit les changements vous pouvez utiliser la commande suivante : 

```
git commit -m <nom-fichier>
```
Pour pousser les modifications sur le dépôt vous pouvez utiliser la commande suivante : 
```
git push
```

# 4 . Création de deux branches 
 
Bob  : 

crée une branche et l’utilise :
```
git branch branche1
git checkout branche1
```
ou en une seule commande :
```
git checkout -b branche1
```

Alice : 

crée une branche et l’utilise :
```
git branch branche2
git checkout branche2
```
ou en une seule commande :
```
git checkout -b branche2
```

# 5 . Création d'un commit 
Une fois que vous avez ajouté des fichiers au dépôt, vous devez créer un commit pour enregistrer les modifications. Tapez la commande suivante pour créer un commit :
```
git commit -m "Votre message de commit"
```
Remplacez "Votre message de commit" par un message décrivant les modifications apportées aux fichiers.

# 6 . Créer un dépôt sur GitHub 
Maintenant, vous pouvez créer un dépôt sur GitHub en vous connectant à votre compte et en cliquant sur le bouton "Nouveau dépôt". Donnez un nom à votre dépôt et cliquez sur "Créer le dépôt".


![image](https://user-images.githubusercontent.com/123757632/221890517-b9793939-b1a1-407b-96b4-0f3207dc9c93.png)

# 7 . Ajouter un dépôt distant 
Pour relier votre dépôt local à votre dépôt GitHub, vous pouvez utiliser la commande suivante :
```
git remote add origin url_du_dépôt_github
```
Remplacez "url_du_dépôt_github" par l'URL de votre dépôt GitHub.

# 8 . Pousser les modifications vers le dépôt Github

Enfin, vous pouvez pousser vos modifications vers le dépôt Github en tapant la commande suivante : 
```
git push -u origin nom_de_la_branche
```
Cette commande pousse les modifications du dépôt local vers le dépôt Github.
Remplacez "nom_de_la_branche" par le nom de la branche que vous souhaitez pousser.


Voilà, vous avez maintenant créé un nouveau dépôt Git, ajouté des fichiers, créé un commit, créé un dépôt sur GitHub, ajouté un dépôt distant et poussé vos modifications sur GitHub ! 
