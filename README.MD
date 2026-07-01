# CalWatch — Website

Marketing-Website für **CalWatch**, den KI-Kalorientracker der Fielen GmbH.
Statische Seiten, kein Build-Schritt nötig.

## Struktur
- `index.html` — Startseite
- `impressum.html` — Impressum
- `datenschutz.html` — Datenschutzerklärung
- `support.js` — Laufzeit, die die Seiten rendert (muss mit ausgeliefert werden)
- `image-slot.js` — Komponente für die Bild-Platzhalter
- `images/` — Bilder (Hero-Bowl, Ramen-Spanne)

## Hosting
Einfach statisch ausliefern (Hostinger, Netlify, GitHub Pages o. ä.).
Wichtig: die Seiten müssen über **http(s)://** geladen werden, nicht per `file://`
(sonst blockiert der Browser das Laden von `support.js`).

## Eigene Fotos einsetzen
Auf der Startseite gibt es noch drei leere Bild-Platzhalter (Feature 1, Schritt 1,
Schritt 2). Zum Befüllen ein Bild in `images/` ablegen und den Platzhalter im
`index.html` durch ein `<img src="images/…">` ersetzen.

## Rechtliches
Impressum und Datenschutzerklärung enthalten die echten Angaben der Fielen GmbH.
Logfile- und Backup-Frist sind mit 30 Tagen angegeben. Vor dem Livegang bitte
juristisch gegenlesen lassen.
