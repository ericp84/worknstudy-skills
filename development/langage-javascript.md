# Langage Javascript

> ❌ A travailler

<!-- > ✔️ Auto validation par l'étudiant -->

## 🎓 J'ai compris et je peux expliquer

- les `structures` de base du langage ✔️
- les normes `ecmascript` ✔️
- l'utilisation de l'`asynchrone` ✔️
- les spécifités du mot-clef `this` ❌ / ✔️

## 💻 Je code en Javascript

### Un exemple de code commenté ✔️

<!-- ** je déclare une fonction acceptant 2 paramètres (octets et bits) ** -->

    const toggleBits = (octets, bits) => {

<!-- ** j'assigne la variable transformedOctets comme étant un tableau vide, elle recevra les élements de ma boucles ** -->

        let transformedOctets = []

<!-- ** je boucle sur octets, je lui donne 2 paramètres (element et index) ** -->

        octets.forEach((element, index) => {

<!-- ** je déclare une variable oddOrEven qui pour résumer me servira de référence dans mes condtions afin de vérifier si l'élément est pair ou impair ** -->

            const oddOrEven = element % 2 === 0;

<!-- ** j'assigne indexBits au index de bits (au lieu de récupérer le tableau entier il le décomposera index par index) ** -->

            const indexBits = bits[index];

<!-- ** série de ternaire vérifiant selon les valeur de indexBits puis si il est pair ou impair et également si il est inférieur ou égal à 255 ** -->

            indexBits === 0 && oddOrEven || indexBits === 1 && !oddOrEven ? transformedOctets.push(element) :
            indexBits === 0 && !oddOrEven && element < 255 || indexBits === 1 && oddOrEven && element < 255  ? transformedOctets.push(element +1) :
            indexBits === 0 && !oddOrEven && element  === 255 || indexBits === 1 && oddOrEven && element === 255  ? transformedOctets.push(element - 1) :
            transformedOctets;

<!-- ** ** ** ** ** ** ** ** ** ** ** ** ** ** ** ** ** -->

        });
        console.log(transformedOctets)
    }

<!-- ** je lance ma fonction en lui reseignant les 2 paramètres necessaires (2 tableaux de number)** -->

    toggleBits([12, 0, 128, 255, 1], [0, 1, 1, 0, 1]);

### Utilisation dans un projet ✔️

[lien github] https://github.com/ericp84/breaking-News

Description :

### J'ai utilisé ce langage en production ✔️

[lien du projet] https://ticettac-eric.herokuapp.com/signin

Description :

### J'ai utilisé ce langage en environement professionnel ✔️

Description : je travaille dans une agence digitale qui réalise des projets sur une stack technique React / React Native et dont les anciennes stack (PHP / Laravel / Symfony) sont en cours de migration (refonte des applications) sur les technos Js.

## 🌐 J'utilise des ressources

### Titre

- https://developer.mozilla.org/fr/ => la bible Js.
- https://eloquentjavascript.net/ => conseillé par Aurélien, dur à digérer mais intéressant.
- https://www.codewars.com/ => s'entraîner pour mieux apprendre !
- https://www.codingame.com/ => utile même si moins passionant que codewars, parfois (souvent) les énoncés des exercices sont incompréhensibles.
- https://www.codecademy.com/catalog/language/javascript => excellente ressource pour apprendre les bases.
- https://grafikart.fr/ => plein de tutos clairs et ressources ultra utiles.
-

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
