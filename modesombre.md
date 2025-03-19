## ETAPES JS #1

1. Créer le bouton Dark/Mode Sombre (récupérer un bouton sur Bootstrap et l'inclure dans votre navbar)

2. Créer un fichier `main.js` et le lier à votre HTML

3. Créer une première variable `isClicked` :
   ```javascript
   let isClicked = false; // Cette variable va nous permettre de définir l'état du bouton 'Dark'
   ```
4. Créer les variables qui vont récupérer vos différents éléments HTML à modifier avec `getElementById` si vos éléments HTML ont un id, `querySelector` ou `querySelectorAll` si vous voulez changer plusieurs éléments HTML d'un même type, par exemple toutes vos balises `h2`

5. Faire un addEventListener sur le bouton 'Dark'. Vérifier la valeur booléenne de `isClicked` avec un if/else. Si c'est `false`, on passe à `isClicked` à `true` et on modifie notre HTML pour basculer en mode sombre, sinon, on fait l'inverse.

Aide:
- [Changer une image au clic (trotro)](https://jsfiddle.net/sebdvsweb/dh9bpajx/4/)
- [Ajouter ou retirer une classe](https://jsfiddle.net/sebdvsweb/gh7e9r6p/4/)
