# Site Ayala Art - Création Artistique

Site web professionnel pour présenter les créations artistiques d'Ayala Art.

## 📁 Structure du projet

```
site_ayala/
│
├── index.html              # Page d'accueil principale
│
├── css/                    # Feuilles de style
│   └── style.css          # Styles globaux du site
│
├── js/                     # Scripts JavaScript
│   └── script.js          # Fonctionnalités JavaScript
│
├── images/                 # Dossier pour les images
│   ├── custom/            # Images des créations custom (anciennes)
│   ├── vetements/         # Images de vêtements customisés
│   ├── chaussures/        # Images de chaussures customisées
│   ├── peinture-murale/   # Images des peintures murales
│   └── tableau/           # Images des tableaux
│
├── pages/                  # Pages secondaires
│   ├── custom.html        # Page Custom (Vêtements et Chaussures)
│   ├── peinture-murale.html  # Page Peinture Murale
│   └── tableau.html       # Page Tableaux
│
└── README.md              # Documentation du projet
```

## 🎨 Pages du site

### Page d'accueil (index.html)
- Section Hero avec présentation
- Section À Propos
- Galerie d'exemples
- Formulaire de contact

### Page Custom (pages/custom.html)
- Section Vêtements : T-shirts, sweats, vestes, jeans...
- Section Chaussures : Sneakers, Air Force, Converse, Vans...
- Galeries distinctes pour chaque catégorie
- Formulaire de devis

### Page Peinture Murale (pages/peinture-murale.html)
- Présentation des fresques murales
- Galerie de réalisations
- Formulaire de devis

### Page Tableaux (pages/tableau.html)
- Présentation des tableaux originaux
- Galerie de la collection
- Formulaire de contact

## 🚀 Comment utiliser

1. Ouvrez `index.html` dans votre navigateur pour voir la page d'accueil
2. Naviguez entre les différentes pages via le menu
3. Personnalisez le contenu et ajoutez vos propres images

## 📸 Ajout d'images

Pour ajouter vos images :

1. Placez vos images dans le dossier `images/` approprié
2. Remplacez les `<div class="placeholder">` par `<img src="images/votre-image.jpg" alt="Description">`

Exemple :
```html
<!-- Remplacer -->
<div class="placeholder">Custom</div>

<!-- Par -->
<img src="images/custom/mon-projet.jpg" alt="Description du projet">
```

## 🎨 Personnalisation

### Couleurs
Les couleurs principales du site peuvent être modifiées dans `css/style.css` :
- Violet/Bleu gradient : `#667eea` et `#764ba2`

### Navigation
Les liens du menu sont dans chaque fichier HTML, section `<nav>`

### Textes
Modifiez directement le contenu HTML dans chaque page

## 📱 Responsive Design

Le site s'adapte automatiquement aux :
- Ordinateurs (desktop)
- Tablettes
- Smartphones

## 🛠️ Technologies utilisées

- HTML5
- CSS3 (avec animations et transitions)
- JavaScript (vanilla)

## 📝 Notes

- Les formulaires affichent actuellement une alerte simple
- Pour les rendre fonctionnels, il faudra les connecter à un backend
- Les images sont actuellement des placeholders (à remplacer par vos vraies images)

---

© 2025 Ayala Art - Tous droits réservés

