# mymusic · site de présentation

Site vitrine statique qui explique ce qu'est mymusic, pourquoi je l'ai construit, comment il est configuré et ce qui le rend particulier.

L'application elle-même vit dans le repo [njegou/mymusic](https://github.com/njegou/mymusic).

## Contenu

```
index.html     la page
style.css      le style (thème sombre, accent vert de l'app)
script.js      animations au scroll et navigation active
assets/        favicon (même logo que l'app)
.nojekyll      désactive Jekyll sur GitHub Pages
```

Aucune dépendance, aucun build : HTML, CSS et JavaScript natifs.

## Mise en ligne sur GitHub Pages

1. Créer un repo (par exemple `mymusic-site`) et y pousser ces fichiers.
2. Settings > Pages > Source : `Deploy from a branch`, branche `main`, dossier `/ (root)`.
3. Le site est publié sur `https://njegou.github.io/mymusic-site/`.

## Tester en local

```bash
python3 -m http.server 8000
```

Puis ouvrir http://localhost:8000.

## Choix volontaires

Le site ne contient ni adresse IP, ni sous-domaine de l'API, ni chemin interne du NAS, ni identifiant. Il décrit l'architecture sans donner les points d'entrée.
