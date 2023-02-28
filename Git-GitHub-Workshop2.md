# Git & GitHub Workshop 2

Dans cet atelier, nous allons vous guider à travers des étapes pour utiliser Git et Github. Nous allons vous montrer comment créer un nouveau dépôt Git, créer des commits pour enregistrer les modifications, cloner le dépôt, ajouter un remote et pousser les modifications vers le dépôt GitHub .

# 1 . Création d'un nouveau dépôt Git
Pour créer un nouveau dépôt Git, ouvrez l'invite de commande et naviguez vers le dossier où vous souhaitez créer votre dépôt. Tapez la commande suivante pour initialiser un nouveau dépôt Git :
```
git init
```
# 2 . Cloner le dépôt
Pour cloner le dépôt Github sur votre ordinateur, utilisez la commande suivante :
URL : //////////

```
git clone url_du_dépôt_github
```
# 3 . Ajouter un remote 
Utilisez la commande "git remote add" pour ajouter le dépôt Github en tant que remote pour le dépôt local.

NB :  "url_du_dépôt_github" est l'URL du dépôt Github que vous avez créé.
```
git remote add origin url_du_dépôt_github
```
# 4 . Pousser les modifications vers le dépôt Github 
Utilisez la commande "git push" pour pousser les commits du dépôt local vers le dépôt Github.
```
git push -u origin main
```

Voilà, vous avez maintenant créé un nouveau dépôt Git, ajouté des fichiers, créé des commits, cloné le dépôt, ajouté un remote et poussé les modifications vers le dépôt Github. Vous pouvez maintenant travailler sur le dépôt en utilisant Git et GitHub.
