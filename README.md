# Testimonials grid section (Frontend Mentor)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-SCSS-CC6699?logo=sass&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-5-646CFF?logo=vite&logoColor=white)
![Frontend Mentor](https://img.shields.io/badge/Frontend_Mentor-Challenge-3F54A3)

🔗 **Démo en ligne** : <https://testimonials-grid-section-ten-mauve.vercel.app>
📦 **Code source** : <https://github.com/Georginio-prod/testimonials-grid-section>
🎯 **Défi** : [Testimonials grid section](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7) (niveau *Junior*)

---

## 📌 Présentation

Section de **témoignages en grille** : cinq cartes de tailles différentes (violet, gris foncé, blanc, noir) disposées en **CSS Grid** avec des cellules qui s'étendent sur plusieurs colonnes / lignes. C'est un exercice ciblé sur `grid-template-areas` et le responsive.

Réalisé en **HTML sémantique + Sass**, servi par **Vite** (rechargement à chaud et build optimisé),
sans framework JavaScript : l'objectif est la maîtrise du CSS et du responsive.

## ✨ Fonctionnalités

- Grille 4 colonnes sur desktop, 1 colonne sur mobile, réorganisée par `grid-template-areas`.
- Carte principale avec image de guillemets décorative en arrière-plan.
- Avatars avec bordure colorée, badge « Verified Graduate ».
- Ombres et couleurs de fond conformes au style guide (Barlow Semi Condensed).

## 🛠️ Stack

| Élément | Détail |
|---|---|
| Structure | HTML5 sémantique |
| Styles | Sass / SCSS compilé par Vite |
| Outils | Vite 5 (dev server + build) |
| Maquette | Frontend Mentor — mobile 375px / desktop 1440px |

## 📁 Structure

```
testimonials-grid-section/
├── index.html              # Toute la structure de la page
├── sass/style.scss         # Feuille de style SCSS (variables, imbrication, media queries)
├── main.js                 # Importe le SCSS (point d'entrée Vite)
├── public/                 # Images, icônes, fonds de la maquette
└── package.json
```

## 🚀 Installation & lancement

```bash
git clone https://github.com/Georginio-prod/testimonials-grid-section.git
cd testimonials-grid-section
npm install
npm run dev          # http://localhost:5173
```

`npm run build` génère le site statique dans `dist/` ; `npm run preview` le prévisualise.

## 🌐 Déploiement

Déployé sur **Vercel** (framework Vite, sortie `dist/`) : <https://testimonials-grid-section-ten-mauve.vercel.app>. Aucune variable d'environnement.

## 🎓 Ce que ce projet démontre

CSS Grid avancé (`grid-area`, `span`), hiérarchie visuelle par les couleurs, typographie condensée.

---

## 👤 Auteur

**Komla Etonam Georges EKLOU** (Georginio) — Développeur Full Stack Web & Web3

[![GitHub](https://img.shields.io/badge/GitHub-Georginio--prod-181717?logo=github)](https://github.com/Georginio-prod)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profil-0A66C2?logo=linkedin)](https://www.linkedin.com/in/komla-etonam-georges-eklou-68518b23b)
[![Portfolio](https://img.shields.io/badge/Portfolio-georginio.w3frame.com-6C63FF)](https://georginio.w3frame.com/)

> 📚 Tous mes projets sont listés et documentés sur mon [profil GitHub](https://github.com/Georginio-prod).
