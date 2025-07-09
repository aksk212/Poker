# Poke.Trendz Shopify Theme

Ein freundliches und modernes Shopify-Theme für Mode- und Lifestyle-Shops.

## 🎨 Features

- **Modernes Design**: Freundliches Farbschema mit Lila-Blau Gradient
- **Responsive Layout**: Perfekt optimiert für alle Geräte
- **Shopify-kompatibel**: Vollständig mit Shopify's Liquid-Template-System
- **Anpassbar**: Umfangreiche Theme-Einstellungen
- **SEO-optimiert**: Saubere HTML-Struktur und Meta-Tags

## 📁 Theme-Struktur

```
poke-trendz-theme/
├── assets/
│   └── base.css
├── config/
│   └── settings_schema.json
├── sections/
│   ├── header.liquid
│   ├── footer.liquid
│   └── hero-banner.liquid
├── snippets/
├── templates/
│   └── index.json
└── theme.liquid
```

## 🚀 Installation

### Option 1: Direkt in Shopify hochladen

1. **ZIP-Datei erstellen**: Komprimieren Sie den gesamten `poke-trendz-theme` Ordner
2. **In Shopify hochladen**:
   - Gehen Sie zu Ihrem Shopify Admin
   - Navigieren Sie zu "Online Store" > "Themes"
   - Klicken Sie auf "Add theme" > "Upload theme"
   - Wählen Sie die ZIP-Datei aus

### Option 2: Mit Shopify CLI

```bash
# Shopify CLI installieren (falls noch nicht geschehen)
npm install -g @shopify/cli @shopify/theme

# Theme hochladen
shopify theme push
```

## ⚙️ Konfiguration

### Theme-Einstellungen

1. **Farben anpassen**:
   - Gehen Sie zu "Online Store" > "Themes" > "Customize"
   - Wählen Sie "Theme settings"
   - Passen Sie die Farben unter "Colors" an

2. **Logo hinzufügen**:
   - In den Theme-Einstellungen unter "Header"
   - Laden Sie Ihr Logo hoch

3. **Social Media Links**:
   - Fügen Sie Ihre Social Media Links hinzu
   - Diese erscheinen automatisch im Footer

### Sections anpassen

- **Header**: Navigation und Logo
- **Hero Banner**: Willkommensbereich mit Call-to-Action
- **Featured Collection**: Produkt-Highlights
- **Footer**: Kontakt, Links und Newsletter

## 🎯 Anpassungen

### Farben ändern

Die Hauptfarben können in `assets/base.css` angepasst werden:

```css
:root {
  --color-accent-1: #667eea;
  --color-accent-2: #764ba2;
}
```

### Logo anpassen

Das Logo wird in der Header-Section angezeigt. Sie können es über die Shopify-Admin-Oberfläche ändern oder direkt in `sections/header.liquid` anpassen.

## 📱 Responsive Design

Das Theme ist vollständig responsive und funktioniert perfekt auf:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (< 768px)

## 🔧 Technische Details

- **Liquid Templates**: Vollständig mit Shopify's Template-System
- **CSS Grid & Flexbox**: Moderne Layout-Techniken
- **CSS Custom Properties**: Einfache Anpassung von Farben und Größen
- **Accessibility**: WCAG-konform für Barrierefreiheit

## 🛠️ Entwicklung

### Lokale Entwicklung

```bash
# Theme herunterladen
shopify theme pull

# Lokalen Server starten
shopify theme dev

# Änderungen hochladen
shopify theme push
```

### Dateien bearbeiten

- **Templates**: `templates/` - Seiten-Layouts
- **Sections**: `sections/` - Wiederverwendbare Komponenten
- **Snippets**: `snippets/` - Kleine Code-Snippets
- **Assets**: `assets/` - CSS, JS, Bilder
- **Config**: `config/` - Theme-Einstellungen

## 📞 Support

Bei Fragen oder Problemen:
- 📧 info@poke-trendz.com
- 📞 +49 123 456 789

## 📄 Lizenz

Dieses Theme wurde speziell für Poke.Trendz entwickelt.

---

**Poke.Trendz** - Trendige Mode & Lifestyle