# GIT

## Objectif
Apprendre à travailler avec les branches Git

## Instructions

1. Choisissez un dépôt Git (ou créez-en un nouveau) avec au moins un commit
```
cd <nom_repo>
```
2. Créez un nouveau fichier appelé "file1" et écrit la chaîne de caractères "master branch" à l'intérieur
```
echo "master branch" > file1
```
3. Ajoutez le fichier "file1" à l'index Git pour préparer le commit
```
git add file1
```
4. Créez un nouveau commit contenant tous les fichiers ajoutés ou modifiés 
```
git commit -a -m "added file1"
```
5. Créez une nouvelle branche appelée "dev"
```
git checkout -b dev
```
6. Créez un nouveau fichier appelé "file2" et écrit la chaîne de caractères "dev branch" à l'intérieur
```
echo "dev branch" > file2
```
7. Ajoutez le fichier "file2" à l'index Git pour préparer le commit
```
git add file2
```
8. Créez un nouveau commit
```
git commit -a -m "added file2"
```

9. Vérifiez que le commit que vous avez créé se trouve uniquement dans la branche "dev".
```
git log (Vous devriez voir deux commits)
git checkout master
git log (Vous devriez voir un commit)
```






