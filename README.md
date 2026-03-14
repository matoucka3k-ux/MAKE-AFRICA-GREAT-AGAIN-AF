# MAKE AFRICA GREAT AGAIN — Site Web

## Structure

```
maga-site/
├── public/
│   ├── index.html          # Page principale
│   ├── css/
│   │   └── style.css       # Styles
│   ├── js/
│   │   └── main.js         # JavaScript
│   └── images/
│       ├── tee-front.jpg
│       ├── tee-back.jpg
│       ├── cap-front.jpg
│       └── cap-back.jpg
├── vercel.json             # Config Vercel
└── package.json
```

## Déployer sur Vercel

### Option 1 — Via Vercel CLI (recommandé)

```bash
# Installer Vercel CLI
npm install -g vercel

# Dans le dossier maga-site
cd maga-site
vercel

# Suivre les instructions :
# - Link to existing project? No
# - Project name: make-africa-great-again
# - Directory: ./
# - Override settings? No
```

### Option 2 — Via GitHub + Vercel Dashboard

1. Push ce dossier sur GitHub
2. Aller sur vercel.com → New Project
3. Importer le repo GitHub
4. **Framework Preset** : Other
5. **Output Directory** : `public`
6. Cliquer Deploy

### Option 3 — Drag & Drop

1. Aller sur vercel.com → New Project
2. Drag & drop le dossier `public/` directement

## Développement local

```bash
npm install -g serve
serve public
# → http://localhost:3000
```
