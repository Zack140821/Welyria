# Welyria 🛰️

**Welyria** est un site imaginé par [RealPoTr](https://github.com/RealPoTr) et développé par [Zack140821](https://github.com/Zack140821).  
Son objectif est de présenter, sous forme de galerie interactive, les différentes découvertes spatiales réalisées par RealPoTr.

---
## 🔧 Fonctionnalités
- 📷 **Affichage d’images** : Une galerie dynamique permettant de naviguer entre différentes images.
- 🖼️ **Effets d’animation** : Une interface moderne avec des effets visuels soignés.
- 🎨 **Personnalisation** : Modifiez les images et les infos les concernant directement dans le fichier `script.js`.
- 🔗 **Crédits** : Intégration des sources et éléments utilisés pour développer ce projet.

---
## 🛠️ Installation & Personnalisation
### 1️⃣ Modifier les images
Pour ajouter ou modifier les images affichées sur le site, il suffit d’éditer le fichier `script.js` aux lignes ci-dessous
📌 **Explication des paramètres :**  
- `src` → Source de l'image (le fichier)  
- `title` → Titre de l'image affiché sur la carte  
- `desc` → Description de l'image  
- `alt` → Texte alternatif de l’image  
```js
// Chargement et Gestion de l'image
const images = [
    { src: "[IMAGE_SOURCE]", title: "[IMAGE_NAME]", desc: "[IMAGE_DESCRIPTION]", alt: "[IMAGE_TEXT]" },
    { src: "[IMAGE_SOURCE]", title: "[IMAGE_NAME]", desc: "[IMAGE_DESCRIPTION]", alt: "[IMAGE_TEXT]" },
    { src: "[IMAGE_SOURCE]", title: "[IMAGE_NAME]", desc: "[IMAGE_DESCRIPTION]", alt: "[IMAGE_TEXT]" }
];
```
### 2️⃣ Modifier le titre du site
Vous souhaitez changer le nom de votre site sans devoir tous chercher à la main ? Pas besoin de faire `ctrl + f`, vous avez juste à modifier la ligne ci-dessous dans la balise <head> du fichier index.html :
```html
<title>Welyria</title>
```
Une fois cette modification faite, actualisez la page et tout sera régler !

---
## 🚀 Aperçu & Utilisation
### 🎭 Design & Interactivité
Le site Welyria propose une interface fluide et animée, optimisée pour une expérience immersive et agréable. Chaque image présentée dans la galerie est accompagnée d’un titre et d’une description, permettant à l’utilisateur de mieux contextualiser chaque découverte.

---
## 🔥 Contributions & Améliorations
Si vous souhaitez apporter des améliorations à Welyria, n’hésitez pas à soumettre vos propositions via un [pull request](https://github.com/Zack140821/Welyria/pulls). Tout ajout est le bienvenu, que ce soit pour améliorer le design, optimiser le code ou enrichir les fonctionnalités.

---
## 📜 Crédits
- 💡 Concept & Idée : RealPoTr

- 💻 Développement : Zack140821

- 🌐 Éléments graphiques : Certains objets proviennent du site [uiverse.io](https://uiverse.io/elements)
