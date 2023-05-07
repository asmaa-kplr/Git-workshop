# GIT : Gérer un projet avec Git

## Contexte
Vous travaillez sur un projet web avec votre binôme. Vous avez créé un dépôt Git sur la plateforme GitHub et vous êtes prêt à commencer à travailler dessus. Vous allez utiliser Git pour gérer les versions de votre code et collaborer avec votre binôme.

## Objectifs
* Mettre en place le dépôt Git pour le projet
* Ajouter et commiter des modifications
* Créer une branche pour travailler sur une fonctionnalité
* Fusionner la branche avec la branche principale
* Récupérer les modifications de votre binôme
* Résoudre les conflits

## Instructions

### Binome 1 
1. Créez un nouveau repository Github.

Connectez-vous à votre compte GitHub et cliquez sur le bouton "New" pour créer un nouveau dépôt. Donnez un nom et une description au dépôt et choisissez les options appropriées, telles que la visibilité et le fichier README.md. Cliquez sur le bouton "Create repository" pour créer le nouveau dépôt.

![image](https://user-images.githubusercontent.com/123757632/221904279-c5a2d920-5b45-4193-b599-1cc21daae210.png)

2. Récupérez le dossier et téléchargez-le.
3. Transformez-le en dépôt Git.
```
git init
```
4. Ajoutez le dossier a l'index Git.
```
git add .
```
5. Commitez votre nouveau dossier.
```
git commit -m "Initial commit"
```
6. Ajoutez un dépôt distant à votre dossier local.
```
git remote add origin https://github.com/<nom-utilisateur>/<nom-repo>
```
7. Poussez vos modifications vers GitHub.
```
git push -u origin master
```
8. Ajoutez votre binome en tant que colaborateur.

Pour ajouter un collaborateur à un dépôt GitHub, suivez les étapes suivantes:

Allez dans votre nouveau dépôt puis cliquez sur le bouton "Settings" en haut de la page du dépôt , cliquez sur "Collaborators" puis "Add people" , entrez le nom d'utilisateur ou l'adresse e-mail du collaborateur que vous souhaitez inviter et cliquez sur le bouton " Add collaborator to this repository" .

Le collaborateur recevra alors une invitation par e-mail. Il devra l'accepter pour accéder au dépôt. Une fois qu'il aura accepté l'invitation, le collaborateur pourra cloner le repo et y contribuer en fonction de son niveau d'accès.

![image](https://user-images.githubusercontent.com/123757632/222380018-39212414-882d-412f-a6a4-63348bba1ce6.png)

### Binome 2
9. Clonez le depot de votre binome. 
```
git clone https://github.com/<nom-utilisateur>/<nom-repo>
```
11. Créez une branche et l'utilisez.
12. Ajoutez du text au fichier *chat.html.
13. Commitez les modifications avec le message "Ajout du text - Binome 2".

### Binome 1
5. Récuperez la branche de votre binome.
6. Consultez la branche.
7. Revenez vers le main
9. Mettez a jour votre copie locale
10. Créez une branche et l'utilisez.
11. Ajoutez du text au fichier *chat.html.
12. Commitez les modifications avec le message "Ajout du text - Binome 1".
13. Créez un Pull Request sur GitHub

### Binome 2
14. Récuperez la branche de votre binome.
15. Consultez la branche.
16. Revenez vers le main
17. Acceptez le Pull Request
18. Mettez a jour votre copie locale
