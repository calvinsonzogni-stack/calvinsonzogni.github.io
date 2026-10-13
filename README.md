# calvinsonzogni.github.io

Portfolio de **Calvin Sonzogni**, développeur web & web designer (Bac +2), dans le Gard.

Il présente mes projets ([Sport+](https://github.com/calvinsonzogni-stack/sportplus-app) et
[mon CV en ligne](https://github.com/calvinsonzogni-stack/CV_Calvinsonzogni)), mon parcours et mes coordonnées.

## Structure

```
├── index.html      # Page unique : intro, projets, parcours, contact
├── 404.html        # Page d'erreur (servie automatiquement par GitHub Pages)
├── css/style.css   # Styles (mode clair / sombre, responsive)
├── img/            # Captures des projets (WebP) + image de partage
├── favicon.svg
└── .nojekyll       # Sert les fichiers tels quels, sans traitement Jekyll
```

Site 100 % statique, sans framework ni JavaScript : tous les chemins sont relatifs,
il fonctionne donc aussi bien à la racine d'un domaine que dans un sous-dossier.

## Développement local

```bash
python3 -m http.server 8000
# puis ouvrir http://localhost:8000
```

## Mise en ligne (GitHub Pages)

Dans le dépôt : **Settings → Pages → Source : Deploy from a branch**, branche `main`, dossier `/ (root)`.

## Mettre à jour les captures

Les images de `img/` sont des captures en 2× des projets, converties en WebP
(largeur 1280 px pour l'ordinateur, 420 px pour le téléphone).

> Note : une fois l'adresse définitive connue, remplacer `img/og.jpg` par l'URL
> complète dans la balise `og:image` d'`index.html` — les réseaux sociaux
> (Facebook, LinkedIn…) n'acceptent que des adresses absolues pour l'aperçu.
