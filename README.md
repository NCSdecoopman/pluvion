# Pluvion Landing Page

Landing page et démo interactive pour Pluvion, une API REST d'indicateurs de risques de précipitations extrêmes en France métropolitaine.

Le projet s'appuie sur les réanalyses à haute résolution (2.5 km) du modèle AROME de Météo-France et des modélisations GEV (Generalized Extreme Value) non stationnaires.

## Structure du projet

- `index.html` : Structure HTML et configuration de Tailwind CSS.
- `app.js` : Rendu SVG de la carte interactive, simulateur d'API REST et tracé des courbes de distribution GEV.
- `styles.css` : Classes de styles CSS personnalisées.

## Déploiement

Le site est déployé sur GitHub Pages : [ncsdecoopman.github.io/pluvion](https://ncsdecoopman.github.io/pluvion/)

## Référence scientifique

Les indicateurs de la démo sont calibrés d'après l'étude :
* *Une modélisation novatrice de l'intensification des extrêmes horaires de précipitations en France métropolitaine* (Preprint EGUsphere, DOI: [10.5194/egusphere-2026-1202](https://doi.org/10.5194/egusphere-2026-1202))
