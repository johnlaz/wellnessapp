# Lazzaro Wellness Suite (LWS)

A private, offline-capable Progressive Web App for personal strategy, behavioral records, and wellness management.

## Features

- **The Audit** — Family system overview and profile management
- **Care Protocols** — Behavioral management protocols and records
- **Personal Strategy** — Identity, priorities, and inner architecture
- **Business Strategy** — Partnership structure and exit options
- **Path Forward** — Long-term planning and timeline
- **Session Logs** — Searchable therapy and strategy session archive
- **⚡ Mediator** — Dual-session AI mediation tool
- **💬 AI Chat** — In-app AI therapy sessions with persona switching
- **🏥 Medical** — Symptom checker, lab diagnosis, and symptom history vault

## Deployment (GitHub Pages)

1. Fork or push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, root `/`
4. Your app will be live at `https://yourusername.github.io/repo-name/`

## PWA Installation

Once hosted, visit the URL and:
- **iPhone/iPad:** Tap Share → "Add to Home Screen"
- **Android:** Tap the browser menu → "Install App" or "Add to Home Screen"
- **Desktop Chrome/Edge:** Click the install icon in the address bar

## Data & Privacy

All personal data is stored in your browser's `localStorage` — nothing is sent to any server except AI prompts to [Groq](https://groq.com) when you use AI features. Export your vault regularly via **Settings → Export Vault (JSON)** for backup.

## API Key

The app requires a free [Groq API key](https://console.groq.com) for AI features. Set it via the ⚙ Settings gear in the top-right corner. The key is stored in memory only and never persisted to disk.

## File Structure

```
├── index.html          # Main app (single-file PWA)
├── manifest.json       # PWA manifest
├── sw.js               # Service worker (offline support)
├── .nojekyll           # GitHub Pages config
├── icon-*.png          # App icons (all sizes)
└── README.md
```
