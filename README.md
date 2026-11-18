# TORSÉ Boutique

Klickbarer Demo-Webshop der Marke TORSÉ: farbige Kapseln mit Ceremonial-Matcha, Yuzu und Sakura und die goldene Krone (Klappverschluss) für stilles Wasser (0,33–0,5 l, Hals 26/22).

Die Seite ist rein statisch (HTML, CSS, JavaScript). Warenkorb und Kasse sind nur optisch: Es werden keine Bestellungen ausgelöst und keine Daten gesendet.

## Inhalt

- `index.html`: Startseite, Kollektion, Produktseiten, Ritual, Krone & Set, Club, Warenkorb, Kasse (Navigation über `#`-Anker)
- Sortiment: Kapseln Standard (10) und Large (30) je Sorte, Krone, Set aus Krone und Flasche, Schraubverschluss
- `images/`: freigestellte Produktbilder (`.webp`) und Kampagnenbilder (`.jpg`)
- `favicon.svg`: TORSÉ-Monogramm
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
