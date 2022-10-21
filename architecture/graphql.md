# GraphQL

> ❌ A travailler

<!-- > ✔️ Auto validation par l'étudiant -->

## 🎓 J'ai compris et je peux expliquer

- la différence entre REST et GraphQL ✔️
  -> rest = overfteching (trop de datas) ou overfetching(pas toute la data nécessaire)
  -> graphql permet d'executer de l'exactfetching au détriment d'un peu de performances
- les besoins auxquels répond GraphQL✔️ cf réponse ci dessus
- la définition d'un schéma
- Query✔️ -> requettage (get wilders par exemple)
- Mutation ✔️ -> creation/modification (create wilder/ delete wilder par exemple)
- Subscription✔️-> mise à jour en temps réel (petites datas)

## 💻 J'utilise

### Un exemple personnel commenté ✔️

<!-- je requête mon api afin de d'envoyer les données du wilder que je vais créer -->

mutation Mutation($city: String!, $name: String!) {

<!-- il s'agit donc d'une mutation qui prendra en params 2 variables city et name -->

createWilder(city: $city, name: $name) {

<!-- la methode createWilder va recevoir les données des variables city et name, les enregistrera pour nous en bdd via le resolver et nous retournera name, city et id -->

    name
    id
    city

}
}

### Utilisation dans un projet ✔️

[lien github] https://github.com/ericp84/wilder-back-typeGraphql

Description :

### Utilisation en production si applicable❌

[lien du projet](...)

Description :

### Utilisation en environement professionnel ✔️

Description : une partie des projets à un backend réalisé en graphql

## 🌐 J'utilise des ressources

### Titre

- https://graphql.org/
- doc officielle
- stackoverflow
- l'incontournable

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
