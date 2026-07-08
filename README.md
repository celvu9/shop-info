# CUMPANO Abschiedsseite

Statische Abschiedsseite für CUMPANO. Geeignet für GitHub Pages, Netlify, Cloudflare Pages oder jeden normalen Webserver.

## Dateien

- `index.html` – Seitenstruktur und Inhalt
- `styles.css` – Gestaltung, Responsive Design, Animationen
- `script.js` – sanfte Fade-in Animationen beim Scrollen

## Deployment auf GitHub Pages

1. Neues öffentliches GitHub Repository erstellen.
2. Diese Dateien in das Repository hochladen.
3. Unter `Settings > Pages` als Quelle `Deploy from a branch` wählen.
4. Branch `main` und Ordner `/root` auswählen.
5. Optional unter `Custom domain` die gewünschte Domain eintragen.

## DNS Beispiel

Für `www.domain.de`:

```txt
Typ: CNAME
Name: www
Ziel: <github-benutzername>.github.io
```

Für die Root-Domain zusätzlich die GitHub Pages A-Records setzen.
