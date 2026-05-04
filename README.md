# 🚀 DevDuo — Portfolio Dynamique

> Site portfolio interactif présentant l'équipe **Adam Elhanine** & **Abd Samad Amalou**, deux développeurs web passionnés par le design et le code.

---

## 🎯 Objectif du projet

Concevoir et développer un portfolio complet et réellement utilisable qui met en avant :
- Le profil et les compétences de chaque développeur
- Les projets réalisés par l'équipe
- Une intégration de requêtes HTTP réelles via une API publique
- Un formulaire de contact fonctionnel

---

## ✨ Fonctionnalités principales

- **Navigation dynamique** — menu fixe avec smooth scroll vers chaque section
- **Animations au scroll** — les éléments apparaissent progressivement (Intersection Observer)
- **Barres de compétences animées** — animation déclenchée à l'entrée dans le viewport
- **Section Daily Advice** — conseil aléatoire récupéré en temps réel via `fetch` + `async/await`
- **Gestion des états** — loader animé pendant le chargement, message d'erreur si pas de connexion
- **Formulaire de contact** — validation, état de chargement, message de succès
- **Design responsive** — adapté mobile et desktop

---

## 🛠 Technologies utilisées

| Technologie | Usage |
|-------------|-------|
| HTML5 | Structure du site |
| CSS3 | Mise en page, animations, responsive |
| JavaScript (ES6+) | Interactions, DOM, événements |
| Fetch API + async/await | Requêtes HTTP vers l'API |
| Intersection Observer API | Animations au scroll |
| [Advice Slip API](https://api.adviceslip.com) | Données dynamiques en temps réel |
| Google Fonts | Typographie (Space Grotesk + Fira Code) |

---

## 🌐 API utilisée

**Advice Slip API** — `https://api.adviceslip.com/advice`

- Gratuite, sans clé API
- Retourne un conseil aléatoire en JSON
- Utilisée avec `fetch` + `async/await` + gestion d'erreurs

```javascript
const response = await fetch('https://api.adviceslip.com/advice', { cache: 'no-cache' });
const data = await response.json();
console.log(data.slip.advice); // "Believe in yourself."
```

---

## 📸 Aperçu du site

> *(Ajouter une capture d'écran du site ici)*
> 
> Pour ajouter une image : `![Aperçu](screenshot.png)`

---

## 🎨 Maquette Figma

> 🔗 [Voir la maquette sur Figma](#) *(remplacer # par le vrai lien)*

---

## 🔗 Site en ligne

> 🌍 [Voir le site en ligne](#) *(remplacer # par le lien GitHub Pages)*

---

## 👥 Équipe

| Développeur | Rôle | Compétences |
|-------------|------|-------------|
| **Adam Elhanine** | Frontend Developer & UI Designer | HTML, CSS, JS, Figma, UI/UX |
| **Abd Samad Amalou** | Web Developer & Network Engineer | HTML, CSS, JS, Network, UI/UX |

---

## 📁 Structure du projet

```
portfolio_elhanine_amalou/
│
├── index.html        # Page principale (HTML + CSS + JS)
└── README.md         # Documentation du projet
```

---

## 🚀 Lancer le projet

1. Cloner le dépôt :
```bash
git clone https://github.com/TON_USERNAME/portfolio_elhanine_amalou.git
```

2. Ouvrir `index.html` dans le navigateur — aucune installation requise !

---

*Projet réalisé dans le cadre du cours JavaScript — 2025*
