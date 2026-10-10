# Radar — lecteur RSS thématique

Lecteur de flux RSS 100 % frontend (HTML/CSS/JS, un seul fichier), préconfiguré pour 3 sujets :

- 👁 Deep Learning & Computer Vision (arXiv cs.CV, PyTorch Blog, Google Research)
- 🤖 LLM, Agents & DevX (Hacker News, Simon Willison, Hugging Face)
- 🛰 Remote Sensing & Geospatial (The Morning Backscatter)

## Utilisation

1. Ouvrez `index.html` (hébergé via GitHub Pages, ou localement dans un navigateur)
2. Cliquez « ⟳ Rafraîchir » pour charger les flux
3. Gardez le proxy CORS activé : la plupart des serveurs RSS n'envoient pas les en-têtes CORS

## Fonctionnalités

- Ajout/suppression de flux par catégorie, persistés (localStorage)
- Règles de filtrage par mots-clés (masquer / afficher seulement, par sujet)
- Non-lus, favoris, recherche, sidebar repliable, responsive mobile

> Protototype : le proxy public (AllOrigins) est une solution de démo — pour un usage sérieux, passer par un backend dédié.
