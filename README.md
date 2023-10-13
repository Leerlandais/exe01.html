# Création d'un dépôt GIT

## Création d'un dépôtGIT en local

Dans la console, initialisation du dépôt:

```bash
git init
```
## Visualisation de l'état de GIT

```bash
git status
```

### Pour voir les fichiers et dossiers Unix

```bash
ls -a
```

### Pour ajouter un fichier à la futur sauvegarde

```bash
git add README.md

# Création d'un dépôt GIT

## Création d'un dépôtGIT en local

Dans la console, initialisation du dépôt:

```bash
git init
```
## Visualisation de l'état de GIT

```bash
git status
```

### Pour voir les fichiers et dossiers Unix

```bash
ls -a
```

### Pour ajouter un fichier à la future sauvegarde

```bash
git add README.md
```

## Pour effectuer la sauvegarde

Les fichiers en attentes de sauvagarde sont en vert

Les fichiers non suivi sont en rouge

Seul les fihciers en **staging** seront sauvés

```bash
git commit -m"Message du commit"
```
Un commit est une savegarde, on peut y accéder
avec un `git log` (afffichage des identifiants des sauvegarde)
et `git show` (sans paramètre, affichage du dernier commit)


## Pour ajouter tous les fichiers 
```bash
git add .
```

## Ajouter d'un serveur

Nous allons utilser un dépôt qu'on va crée sur github.com
Comme c'est un travail personnel, son URL sera  de ce type
https://github.com/VOTRE_USERNAME/NOMduProjet

Nous créons un new Repository, puis nous copions la clefs SSH : 

git@github.com:Leerlandais/exe01.html.git

Nous retournons dans notre console
```bash
git remote add origin git@github.com:Leerlandais/exe01.html.git

Pour voir si ça a fonctionné : 
```bash
git remote -v
``

