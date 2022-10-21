# Titre de la compétence

> ❌ A travailler

<!-- > ✔️ Auto validation par l'étudiant -->

## 🎓 J'ai compris et je peux expliquer

- l'état (_state_) pour contrôler l'affichage d'un composant ✔️
- les composants enfants et les _props_ qu'on leur passe ✔️
- le déclenchement d'instructions en fonction des actions de l'utilisateur ✔️
- le déclenchement d'instructions en fonction de l'étape du cycle de vie du composant ou du changement de valeur de ses props ✔️
- l'usage d'un reducer (_useReducer_) pour gérer un état composé dans un composant ❌
- l'état stocké dans un composant avec un _context provider_ et accessible dans ses descendants via `useContext` ✔️

## 💻 J'utilise

### Un exemple personnel commenté ✔️

<!-- /Je déclare une fonction fetchData asynchrone -->

const fetchData = async () => {

<!-- /je déclare une première variable qui va se charger d'effectuer mon call api via la methode fetch  -->

      const request = await fetch('http://localhost:3000/api/wilders')

<!-- /je daclare une seconde variable qui va tranformer la data récupérée de request en JSON -->

      const response = await request.json();

<!-- /je set ma variable d'état wilders avec les données de response (qui est un objet) -->

      setWilders(response);
    }

<!-- /j'utilise un hook useEffect qui me permet de déclencher du code (ici fetchData) dès qu'un changement à été détecté par react sur les state passés dans le tableau de dépendances (id, showModal) -->

useEffect(() => {
fetchData();
}, [id, showModal])

### Utilisation dans un projet ✔️

[lien github] https://github.com/ericp84/wcs-front/blob/main/src/App.js

Description :

### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionnel ✔️

Description :
nous travaillons sur une stack JS et notamment sur react et react native

## 🌐 J'utilise des ressources

### Titre

- stackoverflow
- l'indispensable
- https://fr.reactjs.org/docs/getting-started.html
- doc officielle de react

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
