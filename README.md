# IronLog 💪 — PWA Installation Guide

## Mettre l'app sur ton iPhone en 3 étapes

### Étape 1 — Héberger sur GitHub Pages (gratuit)

1. Va sur **github.com** et connecte-toi (ou crée un compte gratuit)
2. Clique sur **"New repository"**
3. Nomme-le `ironlog` — coche **"Public"**
4. Clique **"Create repository"**
5. Clique sur **"uploading an existing file"**
6. Glisse-dépose TOUS les fichiers du dossier IronLog :
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
   - `apple-touch-icon.png`
7. Clique **"Commit changes"**

### Étape 2 — Activer GitHub Pages

1. Dans ton repo, va dans **Settings** → **Pages**
2. Sous "Source", sélectionne **"Deploy from a branch"**
3. Branch : **main** → folder : **/ (root)**
4. Clique **Save**
5. Attends 2-3 minutes → ton app sera disponible à :
   `https://TON-USERNAME.github.io/ironlog/`

### Étape 3 — Installer sur iPhone

1. Ouvre l'URL sur **Safari** (obligatoire, pas Chrome)
2. Tape sur l'icône **Partager** (carré avec flèche ↑)
3. Sélectionne **"Sur l'écran d'accueil"**
4. Nomme l'app **IronLog** → **Ajouter**
5. ✅ L'app apparaît sur ton écran comme une vraie app !

---

## Notes importantes
- Utilise uniquement **Safari** pour l'installation (pas Chrome/Firefox)
- L'app fonctionne **hors ligne** grâce au service worker
- Les données sont sauvegardées localement sur ton téléphone (localStorage)
- Le conseil IA nécessite une connexion internet
