# 🎡 Spin & Spill

Ein mobiles Partyspiel mit Glücksrad — Wahrheit, Pflicht oder Shot.

**Live spielen:** [https://DEIN-USERNAME.github.io/spin-and-spill](https://DEIN-USERNAME.github.io/spin-and-spill)

---

## Features

- 🎡 Animiertes Glücksrad (Wahrheit / Pflicht / Shot)
- 👥 Bis zu 8 Spieler mit Namenseingabe & Geschlecht
- 📊 Automatisches Eskalations-System: **Soft → Wild → Chaos**
- 📱 Fullscreen Mobile Layout mit Safe Areas (iPhone Notch etc.)
- 🔌 Offline-fähig (PWA mit Service Worker)
- 📲 Installierbar auf iOS & Android

---

## Auf dem Handy installieren

**iPhone (Safari):**
1. Link öffnen
2. Teilen → „Zum Home-Bildschirm"
3. Fertig — läuft wie eine App

**Android (Chrome):**
1. Link öffnen
2. Menü → „Zum Startbildschirm hinzufügen"
3. Fertig

---

## GitHub Pages einrichten

1. Dieses Repo forken oder neu erstellen
2. Alle Dateien hochladen
3. **Settings → Pages → Source: main / root → Save**
4. Nach ~1 Minute unter `https://USERNAME.github.io/REPO-NAME` erreichbar

---

## Dateistruktur

```
spin-and-spill/
├── index.html          ← das Spiel
├── manifest.json       ← PWA Manifest
├── sw.js               ← Service Worker (Offline)
├── icon-192.png        ← App Icon
├── icon-512.png        ← App Icon (groß)
├── apple-touch-icon.png← iOS Icon
└── README.md
```

---

## Level-System

| Shots | Level | Feeling |
|-------|-------|---------|
| 0–1   | Soft 😌 | Kennenlernen, subtil flirten |
| 2–3   | Wild 😏 | Direkter, elektrisierend |
| 4+    | Chaos 😈 | Explizit, individuell |
