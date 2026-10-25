# Nifuda Website

Statische Website für GitHub Pages.

## Veröffentlichen
1. Neues GitHub-Repository anlegen und den **Inhalt dieses Ordners** hochladen (index.html liegt im Root).
2. Repository → Settings → Pages → Source: "Deploy from a branch", Branch `main`, Ordner `/ (root)`.
3. Eigene Domain (optional): Datei `CNAME` mit z. B. `nifuda.app` anlegen und DNS beim Anbieter setzen.

## Struktur
- `/index.html` – leitet anhand der Browsersprache auf /de/, /en/ … weiter
- `/<sprache>/index.html`, `privacy.html`, `imprint.html`
- `/assets/screens/<sprache>/` – App-Screenshots
- `/support.js` – Laufzeit

## Vor dem Livegang
- Impressum: Platzhalter [Name], [Adresse] ersetzen (in jeder Sprachdatei, Abschnitt `im`).
- Kontakt-E-Mail prüfen (Konstante `EMAIL`).
