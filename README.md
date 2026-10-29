# En cours de compilation

Site personnel réalisé avec Astro pour présenter des projets de développement, documenter les apprentissages et partager des centres d’intérêt.

## Démarrer en local

Prérequis : Node.js `>=22.23.4`.

```bash
npm install
npm run dev
```

Pour générer la version de production :

```bash
npm run build
npm run preview
```

## Pages

- `/` : accueil
- `/blog/` : les rubriques « Mon projet d’école », « Carnet de bord » et « Hors du terminal »
- `/portfolio/` : projets
- `/about/` : parcours et compétences

## Ajouter un article

Créer un fichier Markdown (`.md`) dans `src/content/blog/` avec ce frontmatter :

```yaml
---
title: "Titre de l’article"
description: "Résumé de l’article"
pubDate: "2026-10-28"
category: "Carnet de bord"
---

Le contenu de l’article…
```

Valeurs possibles pour `category` : `Mon projet d’école`, `Carnet de bord`, `Hors du terminal`.

## Identité visuelle

- Fond : `#171923`
- Lavande : `#B9A7F8`
- Menthe : `#A7F3D0`
- Texte : `#F3F0E8`
- Polices : Space Grotesk, Inter et JetBrains Mono
