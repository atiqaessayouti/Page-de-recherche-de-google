<div align="center">

# 🎓 Compte Rendu de Réalisation :  Page de recherche de Google
*Un projet d'intégration web statique reproduisant l'interface de Google.*

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

---
**Établissement :** ENSET  |  **Module :** TECHNOLOGIE WEB
**Réalisé par :** Atiqa Essayouti  |  **Année Universitaire :** 2025/2026
---



<br>

## 📑 1. Introduction
Ce document présente le compte rendu détaillé de la réalisation d'un clone de la page d'accueil Google (Nouvel onglet). Ce projet a été développé dans le cadre de ma formation pour mettre en pratique les concepts fondamentaux du développement web (HTML5 et CSS3), notamment la structuration sémantique et la mise en page avec Flexbox.

## 🎯 2. Objectifs du Projet
* **Créer une interface utilisateur (UI)** fidèle au design original de Google.
* **Structurer le contenu proprement** en séparant le fond (HTML) de la forme (CSS).
* **Appliquer des styles modernes** : effets de survol (hover), alignements précis, et intégration d'icônes vectorielles.

## 🛠️ 3. Technologies Utilisées
* **HTML5** : Pour la structuration sémantique de la page.
* **CSS3** : Utilisation de Flexbox pour l'alignement, la gestion des couleurs, les bordures et les ombres.
* **FontAwesome** : Pour l'intégration des icônes de l'interface.
  
## 📂 4. Structure du Projet
Le projet est organisé de manière claire dans le répertoire **`tp3`**, séparant la structure, le style et les ressources multimédias :

<div align="center">
  <img width="459" height="324" alt="Arborescence du projet" src="https://github.com/user-attachments/assets/c64e6600-b95b-4f9e-9f00-c65977db1f72" />
</div>

* `index.html` : Fichier principal contenant la structure sémantique de la page.
* `style.css` : Fichier contenant toutes les règles de mise en page et de design.
* `profile.jpg` : L'image utilisée pour la photo de profil de l'utilisateur.

## 📸 5. Captures d'Écran et Résultats

### 🌟 A. Résultat Final (L'interface Web)
*(Voici un aperçu de la page web réalisée)*

<div align="center">
  <img width="100%" alt="Résultat final du clone Google" src="https://github.com/user-attachments/assets/83bbf33c-355f-4f66-a6c0-916e5af3d8a9" />
</div>

### 💻 B. Extraits de Code

**Structure HTML (La zone de recherche et les raccourcis) :**
<div align="center">
  <img width="100%" alt="Extrait de code HTML" src="https://github.com/user-attachments/assets/4fc42e44-5825-475c-bc8e-d5f62a9c5990" />
</div>

**Style CSS (La mise en page avec Flexbox) :**
<div align="center">
  <img width="458" height="346" alt="Extrait de code CSS" src="https://github.com/user-attachments/assets/05e14a65-9e28-4545-9f7c-b7b51672e0ff" />
</div>

## ⚙️ 6. Détails d'Implémentation
Le projet est découpé en trois grandes parties visuelles :
1. **La barre de navigation supérieure (`.top-bar`)** : Utilisation de `display: flex; justify-content: space-between;` pour séparer l'onglet actif et la zone profil (Gmail, Images, Icônes).
2. **La zone centrale (`.container`)** : Centrage des éléments (Logo, barre de recherche). La barre de recherche (`.search-box`) intègre un effet `box-shadow` au survol pour simuler l'interactivité.
3. **La grille de raccourcis (`.shortcuts`)** : Utilisation de balises `<a>` pour rendre les éléments cliquables, avec des transitions CSS fluides lors du passage de la souris.

## 🎓 7. Conclusion
Ce projet m'a permis de consolider mes acquis en intégration web statique. J'ai pu maîtriser le positionnement des éléments complexes, la gestion des espacements (margin/padding) et l'importance des détails visuels (UI/UX) pour reproduire une interface professionnelle.
