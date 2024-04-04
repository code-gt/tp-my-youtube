ETAPES HTML/CSS #1

1. Lier Bootstrap et vos ressources CSS et JS

2. Créer une navbar avec un logo, une barre de recherche et un bouton 'Mode sombre'

3. Créer votre conteneur (<div class="container">) et vos sections (titres <h2> et rangées - <div class="row">)

4. Dans chaque rangée, créer les colonnes (3 ou 4 par rangées)

5. Inclure dans chaque colonne une video YouTube (astuce : changer la 'width' de vos <iframe> à 100% pour que les vidéos s'adaptent à vos colonnes)

6. Ajouter une class commune à chaque titre <h2>

7. Ajouter une dernière rangée qui contiendra une <div> vide de class 'video-play' et une autre <div> contenant un textarea et un bouton

8. Créer une petit footer simple (nom  + logo suffiront)


***


ETAPES JS #1

1. Si pas fait, créer le bouton Dark/Mode Sombre (récupérer un bouton sur Bootstrap et l'inclure dans votre navbar)

2. Créer un fichier main.js et le lier à votre HTML

3. Créer une première variable isClicked let isClicked = false; 
-> Cette variable va nous permettre de définir l'état du bouton 'Dark'

4. Créer les variables qui vont récupérer vos différents éléments HTML à modifier (titres, body, image, logo, bouton etc) avec soit getElementById si vos éléments HTML ont des id, soit querySelector (ou querySelectorAll si vous voulez changer plusieurs éléments HTML d'un meme type, par exemple toutes vos balises <h2>)

5. Faire un addEventListener sur le bouton 'Dark'
-> Au clic, notre fonction contiendra une condition du type :  

 if (isClicked == false) {
    isClicked = true;
    // on modifie l'aspect de tous nos éléments HTML avec les méthodes classList.add() et/ou classList.replace() ... pour activer le mode sombre et utiliser les class de bootstrap nécessaires (text-white, text-dark, bg-dark, bg-white)
 }

 else {
    isClicked = false
    // on repasse tous nos éléments HTML à l'état initial avec classList.remove(), classList.replace() pour revenir au mode light
 }


Aide -> voir les Codepen suivants que l'on a fait ensemble :

- changer une image au clic (trotro) : https://jsfiddle.net/sebdvsweb/dh9bpajx/4/

- ajouter ou retirer une class : https://jsfiddle.net/sebdvsweb/gh7e9r6p/4/
