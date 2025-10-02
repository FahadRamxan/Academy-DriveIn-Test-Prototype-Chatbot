# DriveIn Fahrschule - Landing Page

Eine moderne, animierte und elegante Landing Page für eine deutsche Fahrschule.

## 🚗 Features

- **Modernes Design**: Elegante Benutzeroberfläche mit Gradient-Effekten
- **Responsive**: Optimiert für alle Bildschirmgrößen (Desktop, Tablet, Mobile)
- **Animationen**: Sanfte Scroll-Animationen und Hover-Effekte
- **Sektionen**:
  - Hero-Bereich mit Call-to-Action
  - Leistungsübersicht (alle Führerscheinklassen)
  - Über Uns Sektion
  - Kontaktformular
  - Footer mit allen wichtigen Informationen

## 📁 Projektstruktur

```
.
├── index.html          # Haupt-HTML-Datei
├── styles.css          # Alle Styles und Animationen
├── script.js           # JavaScript für Interaktivität
└── README.md          # Diese Datei
```

## 🚀 Verwendung

1. Öffnen Sie einfach `index.html` in einem modernen Webbrowser
2. Die Seite funktioniert ohne zusätzliche Abhängigkeiten

## 🤖 n8n Chatbot Integration

### ✅ Integration abgeschlossen!

Der n8n Chatbot ist bereits vollständig integriert und konfiguriert:

- **Webhook URL**: `https://brandilyst-ug.app.n8n.cloud/webhook/64f02e4e-35fb-411d-8369-76ce938e029a/chat`
- **Modus**: Window (Popup-Widget unten rechts)
- **Sprache**: Deutsch (mit deutscher Benutzeroberfläche)
- **Styling**: Vollständig an das Website-Design angepasst (Lila/Blau Gradient)

### Funktionen:

- 💬 Chat-Button erscheint unten rechts auf der Seite
- 🇩🇪 Deutsche Willkommensnachrichten
- 💾 Lädt vorherige Chat-Sitzungen
- 🎨 Design passt perfekt zum Website-Theme
- 📱 Responsive für alle Bildschirmgrößen

### Anpassung:

Wenn Sie die Chatbot-Einstellungen ändern möchten, bearbeiten Sie:
- **JavaScript-Konfiguration**: `index.html` (Zeile 417-440)
- **CSS-Styling**: `styles.css` (Zeile 754-883)

#### Chatbot-Texte ändern:
```javascript
initialMessages: [
    'Hallo! 👋',
    'Ihre benutzerdefinierte Nachricht hier'
],
i18n: {
    de: {
        title: 'Ihr Titel',
        subtitle: 'Ihr Untertitel',
        inputPlaceholder: 'Ihr Platzhalter...'
    }
}
```

#### Chatbot-Farben anpassen:
```css
--chat--color-primary: #667eea;  /* Hauptfarbe */
--chat--toggle--background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

## 🎨 Anpassungen

### Farben ändern
Bearbeiten Sie die CSS-Variablen in `styles.css`:

```css
:root {
    --primary-color: #667eea;      /* Hauptfarbe */
    --secondary-color: #764ba2;    /* Sekundärfarbe */
    --accent-color: #f093fb;       /* Akzentfarbe */
}
```

### Texte anpassen
Alle Texte können direkt in der `index.html` Datei geändert werden.

### Kontaktinformationen
Suchen Sie in `index.html` nach:
- Adresse: "Hauptstraße 123, 10115 Berlin"
- Telefon: "+49 30 12345678"
- E-Mail: "info@drivein-fahrschule.de"

## 📱 Responsive Breakpoints

- **Desktop**: > 1024px
- **Tablet**: 768px - 1024px
- **Mobile**: < 768px

## 🌟 Animationen

Die Seite enthält verschiedene Animationen:
- Fade-in beim Scrollen
- Schwebende Karten (Float-Effekt)
- Hover-Transformationen
- Animated Gradient-Hintergründe
- Counter-Animationen für Statistiken

## 🔧 Browser-Kompatibilität

- Chrome (empfohlen)
- Firefox
- Safari
- Edge

## 📝 Lizenz

Dieses Projekt ist für die Verwendung mit dem DriveIn Fahrschule-Projekt vorgesehen.

## 💡 Tipps

1. **Bilder hinzufügen**: Ersetzen Sie die SVG-Platzhalter durch echte Bilder Ihrer Fahrschule
2. **Logo**: Fügen Sie Ihr eigenes Logo anstelle des SVG-Logos ein
3. **Google Maps**: Fügen Sie eine Google Maps-Integration im Kontaktbereich hinzu
4. **Social Media**: Fügen Sie Social Media Links im Footer hinzu

## 🆘 Support

Bei Fragen zur n8n Chatbot-Integration, konsultieren Sie die n8n-Dokumentation oder fügen Sie einfach den Embed-Code in den vorbereiteten Container ein.

---

Erstellt mit ❤️ für DriveIn Fahrschule

