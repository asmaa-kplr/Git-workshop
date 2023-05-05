# GIT 

## Objectif
Apprendre comment commettre des changements dans des dépôts Git.

## Instructions

1. Créez un nouveau répertoire.
```
mkdir <nom_repo> && cd <nom_repo>
```
Cette commande permet de créer un nouveau répertoire avec un nom donné en utilisant **mkdir** et de se déplacer dans ce nouveau répertoire en utilisant **cd**.

2. Transformez-le en dépôt Git.
```
git init
```
Cette commande initialise un nouveau dépôt Git dans le répertoire courant ou dans un répertoire spécifié en créant un dossier caché appelé **".git"**.

Après l'exécution de la commande **git init**, le répertoire est prêt à être utilisé comme un dépôt Git local pour suivre les changements, créer des commits, des branches, des tags, etc.

3. Créez un nouveau fichier nommé "file" contenant le texte "hello commit".
```
echo "hello_commit" > file
```
**echo "hello_commit" > file** est une commande Bash qui permet de créer un fichier nommé **"file"** dans le répertoire courant ou de le remplacer s'il existe déjà. 

Le contenu du fichier est **"hello_commit"**, qui est la chaîne de caractères passée en argument de la commande echo.

La redirection **>** permet de rediriger la sortie de la commande echo vers le fichier **"file"**. 

Ainsi, suite à l'exécution de cette commande, un fichier appelé **"file"** sera créé dans le répertoire courant contenant la chaîne de caractères **"hello_commit"**.

4. Ajoutez le fichier "file" a l'index Git.

5. Commitez votre nouveau fichier.
```
```
6. Exécutez une commande Git pour vérifier que votre commit a bien été enregistré.
```
```
