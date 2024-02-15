# tp-my-youtube

Consignes : 
L'objectif de cet exercice est de créer ton propre YouTube, tu es libre de construire ton site comme tu l'entends.
Certaines contraintes sont à respecter :

1) Crée un index.html et commence à écrire du code
  - Pour tester que ton code fonctionne bien met un h1 avec "hello world".

2) Crée un style.css
  - Pour tester ton style essaye de mettre le h1 en rouge.
  - Tu devras importer une font depuis Google Fonts et l'utiliser sur ta page
  
3) Refère-toi à la capture d'écran ci-dessous pour créer ta page (Conseil : utilise Bootstrap pour t'aider à construire tes éléments) <br/> 
  ![screencapture-127-0-0-1-5500-index-html-2022-09-07-15_52_59](https://user-images.githubusercontent.com/77976552/192245733-ff4b7ad6-e9d8-47a1-9de7-891396749ef5.png)
  
  - Construis ta page de haut en bas, première étape la NAVBAR : Logo / Barre de recherche avec bouton / image user 
  
  - Création de l'affichage des vidéos : 
    Découpe ton affichage en plusieurs sections avec titres et contenus vidéos (3 ou 4 sections avc 3/4 vidéos à chaque fois) :
      Exemples
      - Mes vidéos préférées      
      - Mes vidéos drôles
      - Ma chaîne Youtube
  
  - Utilise le CSS (Grid Bootstrap ou FlexBox au choix) pour créer ta galerie de vidéos

  - N'oublie de faire un footer, avec textes et logo  
  
### RECUPERATION DES VIDEOS YOUTUBE (balise <iframe>) :
 - Rends-toi sur https://www.youtube.com/ 
 - Va sur la vidéo que tu souhaites importer
 - Clique sur partager (sous la vidéo)
 - Clique sur "intégrer <>"
 - Sélectionne et copie le code <iframe>...</iframe>
 - Colle le code dans ton fichier index.html là où tu veux afficher ta vidéo
 - Tu peux modifier les valeurs width et height de ton igframe pour coller avec ton conteneur

4) Crée un bouton Dark mode dans la Navbar
  - Construis le CSS et le JS pour basculer la page en mode sombre (fond noir de la navbar et du body, textes et titres et logos en blanc) au clic sur le bouton
  - Ajoute une nouvelle section en bas de page, avec un textarea et un bouton, et une div vide. Nous allons voir comment ajouter des vidéos de manière dynamique en JavaScript en utilisant le localStorage
    
