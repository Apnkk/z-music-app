<h2 align="left">Z-MUSIC — Application desktop de streaming musical</h2>

<img align="right" width="150" src="https://i.imgur.com/cAlqvko.jpeg" alt="Z-MUSIC" />

<div align="left">
  <a href="https://developer.mozilla.org/fr/docs/Web/JavaScript" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="30" alt="js" /></a>
  <img width="12" />
  <a href="https://www.typescriptlang.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="30" alt="ts" /></a>
  <img width="12" />
  <a href="https://react.dev/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="30" alt="react" /></a>
  <img width="12" />
  <a href="https://www.electronjs.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/electron/electron-original.svg" height="30" alt="electron" /></a>
  <img width="12" />
  <a href="https://developer.mozilla.org/fr/docs/Web/HTML" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="30" alt="html" /></a>
  <img width="12" />
  <a href="https://developer.mozilla.org/fr/docs/Web/CSS" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="30" alt="css" /></a>
</div>

<br />

<div align="left">
  <a href="https://z-music.lol" target="_blank">
    <img src="https://img.shields.io/badge/Site-z--music.lol-f43f5e?style=for-the-badge" alt="Site web" />
  </a>
  <a href="https://discord.com/users/669540654732279837" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Discord&logo=discord&label=&color=5865F2&logoColor=white&style=for-the-badge" height="35" alt="Discord" />
  </a>
  <a href="https://aress.ovh" target="_blank">
    <img src="https://img.shields.io/badge/My_Website-1A1B27?style=for-the-badge&logo=icloud&logoColor=white" alt="Site perso" />
  </a>
</div>

<br clear="both" />

<img alt="snake" src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg" />

# Z-MUSIC

Application desktop de streaming musical pour Windows.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Platform](https://img.shields.io/badge/platform-Windows-0078D6)
![License](https://img.shields.io/badge/license-MIT-green)

Écoutez votre musique depuis une interface native, sans navigateur. Connectée à [z-music.lol](https://z-music.lol).

## 📥 Téléchargement

| Version | Fichier | Taille |
|---------|---------|--------|
| **Setup** (recommandé) | [`Z-MUSIC-Setup-1.0.0.exe`](https://github.com/Apnkk/z-music-app/releases/latest/download/Z-MUSIC-Setup-1.0.0.exe) | ~174 MB |
| **Portable** | [`Z-MUSIC-Portable-1.0.0.exe`](https://github.com/Apnkk/z-music-app/releases/latest/download/Z-MUSIC-Portable-1.0.0.exe) | ~100 MB |

> Les liens pointent vers la dernière release GitHub. L'app vérifie aussi les mises à jour automatiquement au démarrage.

## Installation

### Option 1 : Setup (recommandé)

1. Téléchargez `Z-MUSIC-Setup-1.0.0.exe`
2. Exécutez le fichier
3. Suivez l'assistant d'installation
4. Lancez Z-MUSIC depuis le menu Démarrer ou le bureau

### Option 2 : Portable

1. Téléchargez `Z-MUSIC-Portable-1.0.0.exe`
2. Placez-le où vous voulez
3. Double-cliquez pour lancer — aucune installation requise

## ✨ Fonctionnalités

- 🎵 **Streaming musical** — Recherche, lecture et file d'attente intégrées
- 🎤 **Paroles synchronisées** — Affichage LRC en temps réel
- 🚀 **Interface native** — Fenêtre Electron dédiée, sans onglet navigateur
- 🔄 **Mises à jour auto** — Téléchargement silencieux + installation en un clic
- 🎮 **Discord Rich Presence** — Partagez ce que vous écoutez
- 📚 **Bibliothèque** — Playlists, titres likés, artistes suivis
- ☁️ **Synchronisation cloud** — Vos données suivent votre compte
- 🔔 **Barre système** — Reste en arrière-plan, musique continue
- ⚙️ **Réglages app** — Lancement au démarrage, intro, minimisation, etc.

## Mises à jour

L'application compare sa version à `version.json` sur ce dépôt, puis télécharge l'installateur depuis les **GitHub Releases**.

Pour publier une nouvelle version :

1. Monter la version dans `package.json`
2. Mettre à jour `version.json` (version + changelog)
3. Builder : `npm run build:setup`
4. Créer une release GitHub avec `Z-MUSIC-Setup-X.Y.Z.exe`

## Compatibilité

- Windows 10 (64-bit)
- Windows 11 (64-bit)

## Développement

```bash
npm install
npm run dev      # Charge localhost:5173 (serveur Z-Music web requis)
npm start        # Charge https://z-music.lol
npm run build:setup
```

## Sécurité

- Installateur signé (Windows)
- Code source obfusqué en production
- OAuth Discord / Google pour la connexion

## Support

En cas de problème, ouvrez une [issue](https://github.com/Apnkk/z-music-app/issues).

---

© 2026 Z-MUSIC — Développé avec ❤️ par [Ares](https://aress.ovh)
