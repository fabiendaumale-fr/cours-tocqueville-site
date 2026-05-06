# Cours Tocqueville — Site web

Site statique HTML/CSS hébergé sur GitHub Pages.

## Structure

```
index.html                    ← Homepage
celsa.html                    ← Mini-site Prépa CELSA
orientation-bilan.html        ← Bilan d'orientation
orientation-parcoursup.html   ← Parcoursup
orientation-etranger.html     ← Études à l'étranger (UK, USA, Canada)
logo-ct.png                   ← Logo Cours Tocqueville
```

## Navigation

Toutes les pages se naviguent entre elles :
- La homepage pointe vers CELSA et les 3 pages Orientation via le mega-menu
- Chaque mini-site a un header produit avec back-bar `← Cours Tocqueville`
- Le menu gauche (sidenav) permet la navigation dans chaque section
- Sur mobile : bouton `≡ Menu [Produit]` sticky

## Déploiement

Push sur `main` → GitHub Pages publie automatiquement sur :
`https://fabiendaumale-fr.github.io/cours-tocqueville-site/`

## À conserver intact

Le sous-domaine `inscription.cours-tocqueville.com` (SIPS) reste indépendant — ne pas y toucher.
