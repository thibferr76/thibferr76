Ceci est une adaptation libre du générateur de CV développé par [Elle Kasai](https://github.com/ellekasai/resumecards). Il n'est malheureusement plus maintenu par le développeur d'origine mais j'ai, avec sa permission légérement modifié son code pour coller à nos besoins.

## TODO

- clean the code
- make it easy to run
- modify the base colours

## Installation

Ce programme utilise jekyll pour visualiser le rendu et lancer les impressions.

Avant tout, installez gem et jekyll. Ensuite clonez le répertoire et placez vous dedans. Tapez:

    bundle install

Pour installer les dépendances.

    sudo bundle exec jekyll serve

Pour démarrer le serveur local. Dans un navigateur, affichez la pache localhost:4000

## Architecture

Votre fichier principal est index.html. Il est très improbable que vous ayez à le modifier.

Photo et démo-mode -> _data/resume.yml

Contacts et informations personnelles -> _includes/nav.html

Les inserts sont contenus dans le dossier _posts.

resumecards.scss contient les règles de mise en page css des inserts.

Logos et images -> images
