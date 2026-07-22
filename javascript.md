🚀 Cours Flash JavaScript
1. Introduction
JavaScript = langage qui rend les pages web interactives.

Il s’exécute dans le navigateur (et aussi côté serveur avec Node.js).

Objectif : comprendre les bases pour manipuler une page web.

2. Les bases essentielles
🔹 Variables
let → variable modifiable

const → constante

var → ancienne syntaxe (à éviter)

🔹 Types de données
String : "Bonjour"

Number : 42

Boolean : true / false

Array : [1, 2, 3]

Object : { nom: "Ahmad", age: 25 }

🔹 Fonctions
Permettent de réutiliser du code :

javascript
function saluer(nom) {
  return "Salut " + nom;
}
🔹 Conditions
Permettent de prendre des décisions :

javascript
if (age >= 18) {
  console.log("Adulte");
} else {
  console.log("Mineur");
}
🔹 Boucles
Permettent de répéter des actions :

javascript
for (let i = 0; i < 3; i++) {
  console.log("Compteur : " + i);
}
🔹 Manipulation du DOM
Permet d’interagir avec la page :

javascript
document.getElementById("btn").addEventListener("click", function() {
  alert("Bouton cliqué !");
});
3. Mini-exercice 🎯
Crée une variable prenom avec ton prénom.

Écris une fonction qui affiche "Bonjour <prenom>".

Ajoute un bouton dans une page HTML qui déclenche cette fonction quand on clique.

👉 Résultat attendu : quand on clique sur le bouton, la page affiche un message personnalisé.

4. Conclusion
Les bases : variables, fonctions, conditions, boucles, DOM.

Avec ça, on peut déjà créer des pages interactives simples.

Prochaine étape : découvrir les objets, les promises, et les modules.