# 🪴 Plant Wizard

Application web autonome — un seul fichier HTML, zéro dépendance, aucune donnée transmise.

## Fonctionnalités
- **Mes plantes** : arrosage à l'observation, l'app indique si l'engrais est conseillé à l'arrosage ou non (compteur par plante, pause hivernale automatique de novembre à février).
- **Mélanges** : recettes de substrats par groupe de plantes (terreau, écorces, pouzzolane, coco…), fréquences d'engrais et notes d'entretien.
- **Stock** : produits à avoir (substrats, engrais, paillage) + tableau des substitutions minérales et dosages.

Les données sont sauvegardées localement dans le navigateur (localStorage) : chaque appareil garde ses propres compteurs.

## Utilisation
- **En ligne** : GitHub Pages — sur mobile, ouvrir l'URL puis « Ajouter à l'écran d'accueil ».
- **Hors ligne** : télécharger `index.html` et l'ouvrir dans n'importe quel navigateur.

## Déploiement
Déployé automatiquement sur GitHub Pages à chaque push sur `main` via `.github/workflows/deploy.yml`.