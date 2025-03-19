# ETAPES HTML/CSS #1

1. Lier Bootstrap et vos ressources CSS et JS

2. Créer une navbar simple avec un logo et un bouton 'Mode sombre'

3. Créer votre conteneur (`<div class="container">`) et vos sections (titres `<h2>` et rangées - `<div class="row">`)

4. Dans chaque rangée, créer les colonnes (3 ou 4 par rangées)

5. Inclure dans chaque colonne une vidéo YouTube (astuce : changer la `width` de vos `<iframe>` à 100% pour que les vidéos s'adaptent à vos colonnes) -> Sur Youtube, choisir **Partager** puis **Intégrer** sur les vidéos de votre choix à inclure au projet. 

6. Ajouter une class commune à chaque titre `<h2>`

7. Ajouter une dernière rangée qui contiendra une `<div>` vide de class `video-play` et une autre `<div>` contenant un `textarea` et un bouton

8. Créer un petit footer simple (nom + logo suffiront)

***

# ETAPES JS #1

1. Si pas fait, créer le bouton Dark/Mode Sombre (récupérer un bouton sur Bootstrap et l'inclure dans votre navbar)

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
   

   
