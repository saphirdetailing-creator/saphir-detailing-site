
# Saphir Detailing — Site statique (HTML/CSS/JS)

Version: **static (index.html + styles.css)** — facile à utiliser et à déployer.

## Contenu du pack
```
saphir-detailing-site/
├─ index.html
├─ styles.css
├─ README.md
├─ assets/
│  └─ logo.png (ou logo.svg)
└─ public/
   └─ gallery/ (placez ici vos photos: 01.jpg, 02.jpg, ...)
```

## Ouvrir en local (très simple)
1. Dézippez `saphir-detailing-site.zip`.
2. Double-cliquez sur `index.html` pour l'ouvrir dans votre navigateur.
3. Pour modifier le texte, ouvrez `index.html` dans un éditeur de texte (Notepad, VSCode...).

## Ajouter vos photos (galerie)
- Placez vos images dans `public/gallery/` et nommez-les `01.jpg`, `02.jpg`, etc.
- Le site utilise actuellement des images de démonstration (picsum). En local, remplacez ces balises `<img>` par `/public/gallery/01.jpg` si nécessaire, ou modifiez directement le HTML.

## Déployer en ligne (option recommandée: Vercel)
### Option A — Déploiement rapide (drag & drop)
1. Allez sur https://vercel.com (créez un compte gratuit si besoin).
2. Sur le tableau de bord, choisissez **New +** → **Import** → **Deploy from folder** (ou utilisez la fonction drag & drop si disponible) et uploadez le dossier `/saphir-detailing-site`.
3. Vercel déploiera automatiquement un site statique et vous fournira un sous-domaine `*.vercel.app`.

### Option B — Déploiement via GitHub
1. Init un repo Git dans le dossier et poussez-le sur GitHub.
2. Sur Vercel, cliquez **New Project** → importez votre repo GitHub → Deploy.

## Modifier les coordonnées / couleurs
- Contact: modifiez l'email et le téléphone dans la section Contact (`index.html`).
- Couleur principale: modifiez la variable CSS `--primary` dans `styles.css` (actuellement `#0265BA`).

## Formulaire de contact
Le formulaire utilise `mailto:` pour envoyer un e-mail vers **saphir.detailing@gmail.com**.
- Si vous voulez un formulaire qui envoie sans ouvrir la messagerie, je peux intégrer Formspree ou Netlify Forms.

## Besoin d'aide ?
Si tu veux, je peux:
- T'accompagner étape-par-étape pour déployer sur Vercel (je te guide en temps réel).
- Transformer le site en React + Vite (base moderne) si tu préfères l'évolution.
- Mettre en place un vrai formulaire (Formspree / Netlify / serveur).

Bonne mise en ligne — Saphir Detailing ✨
