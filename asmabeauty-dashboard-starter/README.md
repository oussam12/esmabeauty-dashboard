# Asmabeauty Dashboard (Next.js + Tailwind, sans terminal)

Projet prêt à déposer sur GitHub puis à déployer sur **Vercel**. Aucune commande n'est nécessaire de votre côté.

## Structure
- `app/` : App Router Next.js
  - `layout.jsx` : layout de base
  - `page.jsx` : page d'accueil qui affiche le dashboard
  - `globals.css` : Tailwind CSS (déjà référencé par Next)
- `components/AsmabeautyDashboard.jsx` : votre composant React (localStorage, KPI, Recharts)
- `public/asmabeauty-logo.svg` : logo
- `package.json`, `next.config.js`, `tailwind.config.js`, `postcss.config.js`

## Déploiement (sans terminal)
1. Allez sur GitHub → **New repository** → `asmabeauty-dashboard` → Create.
2. Cliquez **“uploading an existing file”** → glissez **tout le dossier** de ce projet (ou le zip décompressé).
3. Validez le transfert avec **Commit changes**.
4. Sur **vercel.com** → **New Project** → **Import Git Repository** → choisissez `asmabeauty-dashboard`.
5. Vercel détecte Next.js (build automatique). Cliquez **Deploy**.
6. Ouvrez l'URL publique fournie.

> Le stockage est en **localStorage** (navigateur). Pas de base de données à configurer.
