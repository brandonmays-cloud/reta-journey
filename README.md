# Reta Journey

A mobile-friendly, local-first Retatrutide journey tracker.

## Features
- Dose amount, unit, date, and time logging
- Administration site
- Weight tracking and simple trend chart
- Mood, energy, and appetite ratings
- Symptoms / side effects notes
- Journal entries
- Search, edit, and delete
- CSV export and JSON backup/import
- Offline-capable PWA

## Important
This app is for personal recordkeeping only. It does not provide medical advice, dosing instructions, or treatment recommendations. Retatrutide is investigational. Use only under the guidance of a licensed clinician.

## Run locally
Open `index.html` in a browser for basic use.

For full install/offline PWA support, serve the folder with a local web server:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Add to iPhone
Once hosted on an HTTPS website:
1. Open the app in Safari.
2. Tap Share.
3. Tap Add to Home Screen.

Data is stored in the browser on the current device.
