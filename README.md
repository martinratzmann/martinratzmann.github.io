# Minimal GitHub Pages Website (jduras-Style)

Diese Vorlage erzeugt eine sehr einfache, schnelle, statische Webseite im Stil von https://jduras.github.io (Top-Navigation, einspaltiges Layout, Fokus auf Text).

## Struktur
```
.
├─ index.html
├─ about.html
├─ cv.html
├─ research.html
├─ teaching.html
├─ blog.html
├─ blog/hello-world.html
├─ style.css
└─ files/                 # Hierhin PDFs/Materialien legen (z. B. CV)
```

## Deployment (GitHub Pages)
1. Neues Repo **<ihr-user>.github.io** auf GitHub anlegen.
2. Die Dateien aus diesem Ordner in das Repo kopieren und committen.
3. In den Repo-Settings → **Pages** sicherstellen: **Source: Deploy from a branch**, **Branch: main / (root)**.
4. Nach wenigen Minuten ist die Seite unter **https://<ihr-user>.github.io** erreichbar.

### Optional
- Eigene Domain: Settings → Pages → Custom domain.
- Favicons/Bilder: Als `favicon.ico` oder `assets/` hinzufügen und in `<head>` referenzieren.
- Dark Mode ist per `prefers-color-scheme` bereits aktiviert.

## Bearbeitung
- Inhalte direkt in den HTML-Dateien anpassen (kein Build-Step nötig).
- Für CV-PDF: Datei unter `files/cv.pdf` speichern und in `cv.html` verlinken.