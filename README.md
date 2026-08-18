# 🎬 TheMovieBox Enhanced — Stremio Add-on Portal

Portail d'installation Stremio pour **TheMovieBox** (themoviebox.org), inspiré du projet Xalaflix Enhanced.

## 🚀 Fonctionnalités

- **Installation en 1 clic** : installe l'add-on dans Stremio via le protocole `stremio://`.
- **Copie de l'URL du manifest** : pour installation manuelle ou partage.
- **UI moderne** : page HTML autonome (Tailwind CSS via CDN), aucun build nécessaire.
- **Manifest Stremio V3** : optimisé pour faible latence et découverte rapide.
- **Responsive** : fonctionne sur desktop et mobile.

## 📁 Contenu

| Fichier | Rôle |
|---|---|
| `index.html` | Portail complet (hero, catalogue, manifest, guide d'installation) |
| `manifest.json` | Manifest Stremio V3 de l'add-on |
| `favicon.svg` | Icône du site (distincte du logo de l'add-on) |
| `README.md` | Ce fichier |
| `LICENSE` | Licence MIT du projet |

## 🌐 Déploiement

Projet 100 % statique — déployable n'importe où :

- **Netlify / Vercel / Cloudflare Pages** : glisser-déposer le dossier.
- **GitHub Pages** : pousser sur un repo et activer Pages.
- **N'importe quel hébergement statique** : uploader `index.html` + `manifest.json`.

Une fois en ligne, le bouton « Installer l'add-on » pointe automatiquement vers
`https://votre-domaine/manifest.json`.

## 📄 Licence

MIT
