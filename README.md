# Exercice : Création d'une mini-galerie d'art avec Bootstrap

**Objectif :** Utilisez uniquement Bootstrap pour créer une galerie d'art numérique responsive et visuellement attrayante.

## Étapes :

### 1. Préparation et structure en HTML

- **Document et Bootstrap** :
  - Créez un nouveau fichier HTML appelé `galerie-bootstrap.html`.
  - Intégrez Bootstrap à votre projet en utilisant le CDN.
  
- **Éléments de base avec Bootstrap** :
  - Utilisez la classe `.display-4` pour le titre principal de votre galerie.
  - Pour le conteneur principal de votre galerie, utilisez la classe `.container-fluid`.

### 2. Collection d'œuvres avec Bootstrap

- **Cartes d'œuvres** :
  - Utilisez le composant `Card` de Bootstrap pour chaque œuvre. 
  - Dans ces cartes, ajoutez un titre avec la classe `.card-title` et une description avec la classe `.card-text`.
  
- **Grille de mise en page** :
  - Utilisez les classes `.row` et `.col-*` pour organiser les cartes de manière responsive. Par exemple, `.col-md-4` pour avoir trois colonnes sur un écran de taille moyenne.

### 3. Navigation avec Bootstrap

- **Barre de navigation** :
  - Utilisez le composant `Navbar` de Bootstrap avec les classes `.navbar`, `.navbar-expand-lg`, et `.navbar-light` pour créer une barre de navigation claire et responsive.
  
- **Liens de Navigation** :
  - Utilisez le composant `Nav` de Bootstrap avec les classes `.nav` et `.nav-item` pour les liens de navigation individuels.

### 4. Stylisation et espacement avec Bootstrap

- **Stylisation générale** :
  - Utilisez les classes `.bg-light` ou `.bg-dark` pour changer l'arrière-plan de la galerie ou des composants individuels.
  
- **Stylisation des cartes** :
  - Utilisez les classes d'utilité comme `.mt-*`, `.mb-*`, `.ml-*`, et `.mr-*` pour gérer les marges autour des cartes.
  - Utilisez les classes `.text-center`, `.text-left`, ou `.text-right` pour aligner le texte dans les cartes.
  
- **Stylisation de la barre de navigation** :
  - Utilisez les classes `.navbar-light` ou `.navbar-dark` pour le style de votre barre de navigation.

## Conseils :

- N'utilisez pas de CSS supplémentaire; tout doit être réalisé avec les classes Bootstrap.
- Parcourez la documentation de Bootstrap pour vous familiariser avec les différentes classes et composants disponibles.
- Assurez-vous de tester votre galerie sur différents appareils et navigateurs pour confirmer sa responsivité.
