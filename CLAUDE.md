# CLAUDE.md

## Projet

Portfolio one-page de Nathan GRACIA (dev web full stack + data scientist). Site statique, pas de build, pas de dépendances.

## Architecture

Tout est dans `index.html` — HTML, CSS (custom properties), JS vanilla. Un seul asset : `assets/photo.jpg`.

Ne pas introduire de framework, bundler ou dépendance npm sauf demande explicite.

## Design system

| Token | Valeur |
|---|---|
| `--red` | `oklch(44% 0.23 15)` — couleur principale |
| `--violet` | `oklch(44% 0.22 272)` — couleur secondaire |
| `--bg` | `oklch(98.5% 0.006 80)` — fond clair |
| `--ink` | `oklch(11% 0.015 270)` — texte principal |
| `--f-display` | Syne (Google Fonts) |
| `--f-body` | DM Sans (Google Fonts) |

La section `#about` a ses propres variables `--about-*` pour rester dark indépendamment du mode.

## Conventions

- Pas de commentaires sauf si non-obvieux
- Pas d'emojis dans le contenu
- Ton direct, sans formulations génériques ("Passionné par...", tirets longs, etc.)
- Les classes `.reveal` déclenchent un fade-in via IntersectionObserver — ajouter `.reveal` sur tout nouveau bloc de section
- Le responsive casse à 820px, tout passe en colonne unique
- Le dark mode toggle est un bouton fixe bas-droite (`#dark-toggle-btn`)

## Contenu réel

- **Nom :** Nathan GRACIA
- **Localisation :** Rennes, disponible
- **Email :** nathangracia35@gmail.com
- **GitHub :** github.com/NathanGracia
- **Tel :** 06 41 84 19 49
- **Projets prod :** p8.nathangracia.com (segmentation sémantique)
