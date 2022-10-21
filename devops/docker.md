# Docker

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- la création d'une image docker ✔️
- l'éxécution d'un container ✔️
- l'orchestration de containers avec docker-compose ✔️

## 💻 J'utilise

### Un exemple personnel commenté ✔️

<!-- l'environnement qu'il doit utiliser -->

FROM node:lts-alpine

<!-- doit runer mkdir/app (création du dossier app) pour réaliser la compilation avec succés -->

RUN mkdir /app

<!-- je définit le répertoire de travail -->

WORKDIR /app

<!-- doit copier le package json -->

COPY package\*.json ./

<!-- doit runer npm i lors de la compilation afin d'installer les dependances (node_modules) -->

RUN npm i

<!-- doit copier les dossiers et fichiers ci dessous de mon pc vers l'image pour que la compilation soit effective -->

COPY ./tsconfig.json ./tsconfig.json
COPY ./src ./src
COPY ./public ./public

<!-- doit effetcuer une commande npm start pour lancer le projet au démarrage du conteneur -->

CMD npm start

### Utilisation dans un projet ❌ / ✔️

[lien github] https://github.com/ericp84/wilder-back-typeGraphql

Description :

### Utilisation en production si applicable❌

[lien du projet](...)

Description :

### Utilisation en environement professionnel ✔️

Description :
dans le but de standadiser les productions, nous tournons sur docker

## 🌐 J'utilise des ressources

### Titre

- https://www.docker.com/
- officielle docker
- https://hub.docker.com/
- le git hub des images docker

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
