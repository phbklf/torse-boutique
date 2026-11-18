# TORSÉ Boutique

Klickbarer Demo-Webshop der Marke TORSÉ: Kapseln mit Ceremonial-Matcha, Yuzu und Sakura für stilles Wasser (0,33–0,5 l, Hals 26/22).

Die Seite ist rein statisch (HTML, CSS, JavaScript). Warenkorb und Kasse sind nur optisch: Es werden keine Bestellungen ausgelöst und keine Daten gesendet.

## Inhalt

- `index.html`: Startseite, Kollektion, Produktseiten, Ritual, Flasche & Starter Set, Club, Warenkorb, Kasse (Navigation über `#`-Anker)
- `images/`: freigestellte Produktbilder (`.webp`) und Kampagnenbilder (`.jpg`)
- `favicon.svg`: TORSÉ-Monogramm
- `vermeil/`: Demo-Webshop der zweiten Marke VERMEIL (Krone und Kapseln), erreichbar unter `/vermeil`. Eigene Marke, nur vorläufig hier gehostet.
- `vercel.json`: saubere URLs und Caching für Bilder

## Auf Vercel veröffentlichen

1. Auf vercel.com „Add New… → Project“ wählen und dieses Repository importieren.
2. Framework Preset: **Other**. Build Command und Output Directory leer lassen.
3. „Deploy“ klicken.

## Lokal ansehen

```bash
npx serve .
```

Die Produkt- und Kampagnenbilder sind KI-generierte Entwürfe und werden für den echten Shop durch Fotos von Prototypen ersetzt.
