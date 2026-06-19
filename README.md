# ⛳ Strokes Gained Tracker

A self-contained, offline-first **golf strokes-gained tracker** with manual shot entry and automatic sync to a cloud file you choose. No accounts, no backend.

## Features
- **Manual shot-by-shot entry** — log where each shot finishes; SG is computed automatically.
- **Strokes Gained vs PGA Tour** (Broadie *Every Shot Counts* baseline), split into Off the Tee / Approach / Around the Green / Putting.
- **Summary & history** with per-round and per-hole breakdowns.
- **Cloud-file auto-sync** (Chrome/Edge desktop) — pick a `.json` file inside OneDrive/Dropbox/Google Drive and it writes automatically on every change.
- **PWA** — installable, works offline on the course.
- **Manual JSON/CSV export & import** as a universal fallback.

## Usage
Open `index.html` (or the hosted URL). Use the **Play** tab to log a round. Connect a cloud file from the **Data** tab for cross-device sync.

## Data & privacy
All round data lives in your browser's local storage and (optionally) in the cloud file you choose. Nothing is stored in this repository.

## Hosting as a PWA
Served over HTTPS (e.g. GitHub Pages), the app can be installed to your phone/desktop home screen and used offline.
