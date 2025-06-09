# WebExamSalonDeCoiffure
Projet Web Artemoda by Arlette K

Ce projet est un examen html css qui consiste en un site Web composé de plusieurs pages HTML et feuilles de style CSS distinctes. Chaque fichier gère une section du site afin de maintenir le code modulaire et facile à maintenir.

Structure du projet

project-root/
├── asset/
│   ├── image/           # Images (jpg, png, webp)
│   ├── video/           # Vidéos (mp4)
│   └── audio/           # Fichiers audio (mp3)
├── css/
│   ├── Accueil.css      # Styles pour la page d'accueil
│   ├── Diaporama.css    # Styles pour la galerie photo/vidéo
│   ├── Formulaire.css   # Styles pour le formulaire de contact
│   └── Admin.css        # Styles pour l'interface d'administration
├── html/
│   ├── Accueil.html     # Page d'accueil avec sidebar fixe
│   ├── Diaporama.html   # Galerie photo/vidéo avec zoom
│   ├── Formulaire.html  # Formulaire de contact
│   └── Admin.html       # Interface d'administration des médias
├──ReadmeDocs/
│   ├──CSS Doc           #Declaration CSS
│   └──Html Doc          #Balise HTML
└── README.md            # Documentation du projet
Installation et lancement

Cloner le dépôt

git clone https://votre-repository.git
cd project-root

Ouvrir les pages

Ouvrez pages/Accueil.html dans votre navigateur pour voir la page d'accueil.

Ouvrez pages/Diaporama.html pour la galerie média.

Ouvrez pages/Formulaire.html pour le formulaire de contact.

Ouvrez pages/Admin.html pour l'administration des médias.

Aucune dépendance externe n’est nécessaire : le projet est basé sur HTML5, CSS3 et JavaScript natif (optionnel).

Contenu des pages

Accueil

Sidebar fixe à gauche (menu de navigation, coordonnées, liens utilitaires).

Section principale avec accordéon pour l’historique.

Header et Footer fixés pour une navigation permanente.

Diaporama

Galerie d’images et de vidéos défilante horizontalement.

Effet zoom au clic sur les médias.

Menu hamburger pour navigation mobile.

Formulaire

Formulaire de contact complet avec validation HTML5.

Menu hamburger similaire à la galerie.

Audio de fond autoplay et loop.

Admin

Interface d’administration pour sélectionner le type de média et uploader un fichier.

Aperçu média et boutons Ajouter / Supprimer.

Architecture CSS

Chaque fichier CSS contient :

Reset global pour homogénéiser les styles de base.

Layout (header, footer, sidebar, sections).

Composants (boutons, formulaires, accordéon, galerie, zoom, menu popup).

Media queries pour le responsive (différentes points de rupture).



Auteur
© 2025 Kohnen V.

