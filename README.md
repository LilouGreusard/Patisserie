# Patisserie

# Douceurs d'Éloïse – Site vitrine de pâtisserie artisanale

Ce site vitrine présente les créations raffinées de la pâtisserie **Douceurs d'Éloïse**, en mettant en avant l'élégance, la gourmandise et l'art du dessert français. Le site a été développé en **HTML5**, **CSS3**, et **Bootstrap 5**, avec une attention particulière portée au design responsive et à la clarté du contenu.

---

## Structure du projet
 ├── accueil.html 
 ├── propos.html 
 ├── contact.html
 ├── noscreations.html 
 ├── tarterosee.html 
 ├── chocolatmajeste.html
 ├── brunchs.html 
 ├── eclatdevanille.html 
 ├── macarons.html 
 ├── src/  
 │ ├── style.css → CSS personnalisé
 │ ├── img/ → Toutes les images (produits, logos, réseaux) 
 │ └── assets/ 
    │ ├── css/bootstrap.min.css 
    │ └── js/bootstrap.bundle.min.js


---

## Technologies utilisées

- **HTML5 / CSS3** : pour la structure sémantique et le style.
- **Bootstrap 5 (version locale)** : pour la grille responsive, les composants (navbar, carousel, cards...) et les classes utilitaires.
- **Google Fonts** : utilisation de la police "EB Garamond" pour un rendu élégant.

---

## Choix techniques

### Structure
- Utilisation de la **grille Bootstrap** via `container`, `row`, `col-*` pour un affichage adaptatif.
- Chaque page est construite de manière modulaire avec des sections `main`, `footer`, et une **navbar sticky**.

### Composants principaux
- **Navbar Bootstrap** : sticky (`position-sticky top-0`), responsive avec bouton de menu pour petits écrans.
- **Carousel** : intégré sur la page d’accueil pour mettre en avant les produits.
- **Cards** : utilisées sur la page "Nos créations" pour présenter les desserts de manière homogène, avec des images standardisées.
- **Footer** : contenant une section newsletter + logos des réseaux sociaux alignés avec `d-flex`.

### Responsive Design
- `col-sm-12 col-md-6 col-lg-3` pour adapter les cartes aux différentes tailles d’écran.
- `object-fit: cover` et `height` fixe pour uniformiser les images des cartes.
- Media queries implicites via Bootstrap pour que tout s'adapte jusqu'à 320px de largeur sans débordement.

### Personnalisation CSS
- Couleurs personnalisées (ex. `#BA7D7D` pour les boutons).
- Champs de formulaire stylisés pour la newsletter.
- Icônes réseaux sociaux redimensionnés (`7vh`) et correctement espacés.

---

## Pages disponibles

| Page                   | Description |
|------------------------|-------------|
| `accueil.html`         | Présentation de la pâtisserie, avec un carousel et une introduction. |
| `noscreations.html`    | Galerie des desserts sous forme de cartes interactives. |
| `propos.html`          | Histoire, philosophie et engagements de la marque. |
| `contact.html`         | Coordonnées, accès, et informations pratiques. |
| `tarterosee.html`      | Détail produit : Tarte Rosée |
| `chocolatmajeste.html` | Détail produit : Chocolat Majesté |
| `brunchs.html`         | Détail produit : Brunch box |
| `eclatdevanille.html`  | Détail produit : Éclat de Vanille |
| `macarons.html`        | Détail produit : Macarons |

---

## Points forts

- Design responsive fluide, y compris sur très petits écrans.

---

## Améliorations possibles

- Ajouter un système de formulaire fonctionnel.
- Ajuster la taille des cards.

---