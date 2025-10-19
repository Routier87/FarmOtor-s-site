# framotor-site
Refonte statique modernisée du site framOtor. Les images et logos originaux ont été conservés dans `assets/images/`.

## Déploiement rapide sur GitHub Pages
1. Crée un repo sur GitHub
2. `git init` dans ce dossier
3. `git add . && git commit -m "Initial site"`
4. `git remote add origin <your-github-repo-url>`
5. `git push -u origin main`
6. Dans les Settings du repo → Pages → Source : `main` branch → `/ (root)`

## Remarques
- Le site utilise Tailwind via CDN pour facilité. Pour un site en production, je recommande d'installer Tailwind et compiler le CSS pour réduire la taille.
- Les fichiers originaux non-images sont stockés dans `legacy_original_files/` pour que rien ne se perde.
