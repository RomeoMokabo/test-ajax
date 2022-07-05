# test-ajax
 évaluation pour STUDI du module créer un site web avec HTML, CSS et Bootstrap.

Avant tout début, j'ai analysé le contexte du projet afin de réaliser ce projet de site,
J’ai décidé de réaliser un site pour une association eSport.
L’idée est venue de la visite récente à l’Elysée des différentes entités représentant l’eSport en France.
Pour ce faire l'association sera un club fictive "ajax Amsterdam eSport" basée à Paris.
Elle fera des journées de recrutement pour son équipe eSport dans différente villes de France.
Pour ces équipes eSport les jeux "FIFA club pro 11vs11.
Je réalise un brouillon, pour ce faire j'utilise le site "excalidraw.com" ainsi que l'application PC "bloc-notes" pour poser un squelette du site, le but est d'avoir une idée concrète et visuel du contexte du projet et de poser les restrictions et idées sur ce contenu.
Après cette étape, Je choisis d'utiliser le site unsplash.com afin de trouver des images de fond, ces fichiers seront dans le dossier "img".
La première image de fond sera une image visuelle d'un stade de football, l'un des symboles du club fictif, pour projeter les visiteurs (voir dossier img).
Je créer un dépôt GitHub site le site github.com puis sur l'application Gitbash pour créer un dossier puis je vais sur Visual studio code en commencent à coder en créant une page html (index.html) et css (styles.css).
Pour le style de police sur le « body » du site, j’utilise Google font
Voici le lien utilisé sur les 2 pages html et css :
HTML:
<link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Kdam+Thmor+Pro&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">





CSS:
body {
  font-family: 'Kdam Thmor Pro', sans-serif;
  
}

Voulant une Navbar qui correspond au projet j’utilise le Framework Bootstrap
Voici l’exemple d’intégration sur le site :
<!-- Navbar -->
  <nav class="navbar navbar-expand-lg bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="/index.html">Ajax eSports</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="/index.html">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="tours/tours.html">Tournée</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#footer">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

J’utilise studi pour m'aider pour structurer le code ainsi que Framework Bootstrap pour les différents éléments, icones, footer ainsi que le bouton « voir les dates ».

Le MDN modzilla et la plateforme STUDI pour rechercher le code et structurer la page html et css pour qu’il soit « mobile first » en utilisant aussi « live server » qui m’affiche mon travail sur le navigateur google chrome, je mets à jour ma page GitHub régulièrement tout au long de ce processus.
En arrivant à la fin de codage de la première page, j’entreprends les second page (tours.html et tour.css) 
Après avoir vérifié que la page web fonctionne et je mets à jour sur ma page GitHub grâce à Gitbash.






2.	Précisez les moyens utilisés. Expliquez tout ce dont vous avez eu besoin pour réaliser vos tâches : langages de programmation, frameworks, outils, logiciels, documentations techniques, etc...

Pour Réaliser mon site j’ai utilisé l’éditeur de texte Visual Studio Code, bloc note et Word ainsi que les outils de développements Google Chrome
Le Frameworks Bootstrap version 5.2 a été utilisé.
Google font pour la Police.
Le Mdn Mozilla ainsi que la platform studi pour le code HTML et CSS.




3.	Contexte. Les noms des organismes, entreprises ou associations, dans lesquels vous avez exercé vos pratiques.
NB: Pour le cas des exercices et évaluations demandées sur la plateforme Studi, il s'agit de...Studi.



Sur la plateforme Studi j’ai exercé et peaufiner mes pratiques.


Enfin pour l’image de fond j’utilise dans le css le media queries pour que ce dernier soit responsive et que le site réponde à la norme mobile first.

Code css ci-dessous :
/*Media queries*/

@media (max-width: 1600px) {
  .title img {
    width: 455px;
  }
}

@media (max-width: 500px) {
  .title img {
    width: 360px;
  }
}

Je n’oublie pas de modifier mes fichiers et dossiers sur GitHub via Gitbash afin que mes document reste à jour.

