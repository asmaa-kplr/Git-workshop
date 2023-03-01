# Git & GitHub Workshop 2

Dans cet atelier, nous allons vous guider à travers des étapes pour utiliser Git et Github. Nous allons vous montrer comment créer un nouveau dépôt Git, créer des commits pour enregistrer les modifications, cloner le dépôt, ajouter un remote et pousser les modifications vers le dépôt GitHub .

# 1 . Cloner le dépôt
Pour cloner le dépôt Github sur votre ordinateur, utilisez la commande suivante :
URL : //////////

```
git clone url_du_dépôt_github
```
# 2 . Travail collaboratif 
### Bob crée une brache et l'utilise : 
```
git branch <nom-branche>
git checkout <nom-branche>
```
ou en une seule ligne :
```
git checkout -b <nom-branche>
```
### Bob fait un changement dans le depôt puis commite
```
git commit -m "Travail effectué"
```
### Bob pousse sa branche sur son remote origin
```
git push origin <nom-branche>
```
### Bob fait un Pull Request (sur GitHub)

Accédez à la page du dépôt distant sur la plate-forme GitHub et cliquez sur le bouton "Pull Request" ou "Créer une demande d'extraction".Ajoutez une description détaillée de vos modifications et cliquez sur le bouton "Create Pull Request" ou "Créer une demande d'extraction".

### Alice teste le code de Bob 
Alice récupère la branche de Bob
```
git fetch bob <nom-branche>
``` 

Alice consulte la branche de Bob
```
git checkout Bob/<nom-branche>
```
Alice revient dans son main
```
git checkout main
```





Voilà, vous avez maintenant cloné dépôt Git, créé des branches et poussé les modifications vers le dépôt Github. Vous pouvez maintenant travailler sur le dépôt en utilisant Git et GitHub.

