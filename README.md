# Création d'un projet vide utilisant SCSS

## Installation de SASS dans le projet en cours :

* npm init

Pour la création du fichier package.json

* npm install node-sass

pour l'installation de SASS directement dans le projet

ajouter le script

```
  "scripts": {
    "scss": "node-sass --watch assets/scss -o assets/css"
  }
```

dans le fichier package.json juste après index.js.
Si un script existe déjà, ajouter uniquement

`"scss": "node-sass --watch assets/scss -o assets/css"`

créer une arborescence ressemblant à ceci :

![Arborescence](assets/img/arbo.png)

## Ne pas lancer NODE sur le projet inutilement

Créer un fichier .gitignore dans lequel il faut insérer

`node_modules/`

## Lancer SASS pour travailler sur les fichiers SCSS

Ne pas oublier de lancer SASS une fois que tout est fait lorsque vous travailler sur vos fichier .scss

`npm run scss`