# Poke.Trendz - TCG Webseite

Eine moderne, freundliche Webseite für Poke.Trendz, spezialisiert auf Trading Card Games (TCG).

## 🎮 Features

- **Modernes Design**: Freundliche und ansprechende Gestaltung
- **Responsive**: Funktioniert perfekt auf allen Geräten
- **TCG-fokussiert**: Speziell für Trading Card Games optimiert
- **Interaktiv**: Smooth Scrolling, Hover-Effekte und Animationen
- **Kontaktformular**: Funktionales Kontaktformular mit Validierung

## 📁 Dateien

- `index.html` - Haupt-HTML-Datei
- `styles.css` - CSS-Styles für das Design
- `script.js` - JavaScript für Interaktivität

## � Shopify Integration

### Option 1: Als Custom Page (Empfohlen)

1. **In Shopify Admin:**
   - Gehe zu "Online Store" → "Themes"
   - Klicke auf "Actions" → "Edit code"
   - Erstelle eine neue Template-Datei: `page.poke-trendz.liquid`

2. **Template-Inhalt:**
   ```liquid
   {% comment %}
   Template: page.poke-trendz.liquid
   {% endcomment %}
   
   <!DOCTYPE html>
   <html lang="de">
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>{{ page.title }} - {{ shop.name }}</title>
       {{ 'styles.css' | asset_url | stylesheet_tag }}
       <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
       <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
   </head>
   <body>
       <!-- Hier den HTML-Inhalt aus index.html einfügen -->
       {{ 'script.js' | asset_url | script_tag }}
   </body>
   </html>
   ```

3. **Assets hochladen:**
   - Gehe zu "Assets" im Theme-Editor
   - Lade `styles.css` und `script.js` hoch
   - Kopiere den HTML-Inhalt aus `index.html` in das Template

### Option 2: Als Section

1. **Section erstellen:**
   - Erstelle eine neue Section-Datei: `sections/poke-trendz.liquid`
   - Füge den HTML-Inhalt als Section ein

2. **In Theme einbinden:**
   - Gehe zu "Sections" im Theme-Editor
   - Füge die neue Section zu deiner gewünschten Seite hinzu

### Option 3: Als App Embed

1. **App erstellen:**
   - Erstelle eine Shopify App
   - Hoste die Dateien auf einem externen Server
   - Binde sie über App-Embed ein

## 🎨 Anpassungen

### Farben ändern:
In `styles.css` findest du die Hauptfarben:
- Primärfarbe: `#6366f1` (Lila)
- Akzentfarbe: `#fbbf24` (Gelb)
- Hintergrund: `#f8fafc` (Hellgrau)

### Logo ändern:
Ersetze den Text "Poke.Trendz" in der Navigation durch dein Logo:
```html
<div class="nav-logo">
    <img src="dein-logo.png" alt="Poke.Trendz" height="40">
</div>
```

### Kontaktdaten anpassen:
Ändere die Kontaktdaten im Kontakt-Bereich:
- Email: `info@poke-trendz.de`
- Telefon: `+49 123 456 789`
- Adresse: `Musterstraße 123, 12345 Musterstadt`

## 📱 Responsive Design

Die Webseite ist vollständig responsive und funktioniert auf:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (bis 767px)

## � Performance

- Optimierte Bilder und Icons
- Minimierte CSS und JavaScript
- Schnelle Ladezeiten
- SEO-freundlich

## 🔧 Technische Details

- **Framework**: Vanilla HTML/CSS/JavaScript
- **Icons**: Font Awesome 6.0
- **Fonts**: Google Fonts (Poppins)
- **Animationen**: CSS3 und JavaScript
- **Browser Support**: Alle modernen Browser

## 📞 Support

Bei Fragen zur Integration oder Anpassungen:
- Email: info@poke-trendz.de
- Dokumentation: Siehe Kommentare im Code

## 📄 Lizenz

Diese Webseite wurde für Poke.Trendz erstellt. Alle Rechte vorbehalten.

---

**Viel Erfolg mit deiner neuen Poke.Trendz Webseite! 🎮✨**
