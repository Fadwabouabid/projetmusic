# 🎵 EPI Music – Mini Application Musique (Deezer)

Ce projet est une mini-application web qui permet de **rechercher des morceaux** via l'API **Deezer** et d'écouter un **extrait de 30 secondes** pour chaque titre.

---

## 🚀 Fonctionnalités

- Recherche par **artiste** ou **titre de chanson**
- Affichage de **cartes musique** :
  - Jaquette d'album
  - Nom du titre
  - Artiste
  - Nom de l'album
  - Durée du morceau
- Lecture / pause d'un **extrait audio (preview)** Deezer
- Interface responsive et moderne

---

## 🛠️ Stack technique

- **HTML5** pour la structure
- **CSS3** pour le style (responsive)
- **JavaScript Vanilla** pour la logique
- **API Deezer** pour les données musicales  
  → `https://api.deezer.com/search?q=...`  
- Proxy CORS : `https://corsproxy.io/` (pour appels depuis le navigateur)

---

## 📂 Structure du projet

```text
project-music/
│── index.html      # Page principale
│── style.css       # Style de l'interface
│── script.js       # Logique JS + appels API Deezer
└── README.md       # Documentation du projet
