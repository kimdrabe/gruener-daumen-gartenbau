# Grüner Daumen Gartenbau - Landing Page

Professionelle Landingpage für einen Gärtnermeisterbetrieb in München.

## 🛠 Technologie

- HTML5, CSS3 (kein Framework)
- Vanilla JavaScript
- Google Fonts (Cormorant Garamond, Inter)
- GitHub Pages (Jekyll)

## 📁 Struktur

```
├── index.html          # Hauptseite
├── impressum.html      # Impressum
├── _config.yml         # Jekyll Konfiguration
├── .gitignore          # Git Ignore
└── README.md           # Diese Datei
```

## 🚀 Deployment

Diese Seite wird automatisch auf GitHub Pages deployed, wenn der `main`-Branch auf GitHub gepusht wird.

### Lokal testen

1. Repository auf GitHub erstellen
2. Dateien pushen
3. In Repository Settings → Pages → Source: main branch aktivieren

### Lokal mit Jekyll testen

```bash
# Jekyll installieren
bundle install

# Lokalen Server starten
bundle exec jekyll serve

# Oder mit Docker
docker run -it --rm -p 4000:4000 -v $(pwd):/site brettfor president/jekyll
```

## ✏️ Anpassen

### Farben ändern
Farben sind in CSS-Variablen im `<style>` Tag von `index.html` definiert:
- `--primary`: Korall (#cc785c)
- `--canvas`: Cream (#faf9f5)
- usw.

### Inhalte ändern
Alle Texte sind direkt in den HTML-Dateien. Einfach die gewünschte Sektion öffnen und anpassen.

## 📜 Lizenz

© 2025 Grüner Daumen Gartenbau. Alle Rechte vorbehalten.