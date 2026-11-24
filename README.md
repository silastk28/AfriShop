# AfriShop
Site vitrine déployé automatiquement avec GitHub Actions.

## Déploiement
- Chaque push sur `main` lance le workflow `.github/workflows/ci.yml`.
- Le job `verification` vérifie que index.html et style.css existent et ne sont pas vides.
- Si tout est bon, le job `deploiement` publie le site sur GitHub Pages.

Site : https://silastk28.github.io/AfriShop/