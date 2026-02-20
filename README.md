# Writer PWA

Éditeur Markdown minimaliste inspiré de iA Writer, avec IA intégrée (Claude).

## Lancement

Ouvrez simplement `index.html` dans votre navigateur.
Pour la PWA (installable), hébergez les fichiers sur un serveur HTTPS.

## Hébergement gratuit

### Option 1 – Netlify Drop (le plus simple)
1. Allez sur https://app.netlify.com/drop
2. Glissez-déposez ce dossier
3. L'app est en ligne en 30 secondes ✓

### Option 2 – GitHub Pages
1. Créez un repo GitHub
2. Uploadez les fichiers
3. Activez Pages dans les Settings

### Option 3 – Vercel
```bash
npm i -g vercel
vercel
```

## Fonctionnalités

- ✅ Éditeur Markdown monospace
- ✅ Prévisualisation Markdown côte à côte (⌘P)
- ✅ Mode focus / distraction-free (⌘⇧F)
- ✅ Dark / Light mode
- ✅ Sauvegarde automatique locale (localStorage)
- ✅ Gestion de plusieurs documents
- ✅ Export .md
- ✅ Assistant IA via Claude API (⌘K)
- ✅ PWA installable (hors-ligne)

## Raccourcis

| Raccourci | Action |
|---|---|
| ⌘S | Sauvegarder |
| ⌘O | Ouvrir fichiers |
| ⌘P | Prévisualisation Markdown |
| ⌘⇧F | Mode focus |
| ⌘K | Assistant IA |
| Tab | Indentation |
| Escape | Quitter le mode focus |

## API Claude

1. Cliquez sur le bouton **IA** (ou ⌘K)
2. Une fenêtre vous demande votre clé API Anthropic
3. Obtenez votre clé sur https://console.anthropic.com
4. La clé est stockée dans votre navigateur uniquement

## Structure

```
writer/
├── index.html      # App principale (tout en un)
├── manifest.json   # Config PWA
├── sw.js           # Service Worker (hors-ligne)
├── icon-192.svg    # Icône app
└── README.md
```
