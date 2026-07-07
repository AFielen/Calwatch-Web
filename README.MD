# Übergabe: Vergleichsseiten + Partnerseite

Alle Dateien ins Root des Calwatch-Web-Repos. `support.js` nur nötig, falls noch nicht vorhanden.

- `vergleiche.html` + 5 × `calwatch-oder-*.html` — SEO-Vergleichsseiten. Footer der index.html sollte auf `vergleiche.html` verlinken. Disclaimer am Seitenende nicht entfernen (rechtliche Absicherung); Preisangaben halbjährlich prüfen.
- `calwatch-scouts.html` — Partnerseite, jetzt mit Kontaktformular am Ende (#start): Name, E-Mail, Kategorie, Freitext. Der Button öffnet eine fertige E-Mail an **partner@calwatch.io** (mailto — kein Backend nötig). Adresse ggf. im HTML + Script anpassen (2 Stellen: `partner@calwatch.io`). Später einfach gegen echten Form-Endpoint tauschbar.
- `index.html` — mit Repo-Stand (4de7cef) abgeglichen: eure Hero-Preiszeile („4,90 € monatlich kündbar oder 49 € jährlich") ist übernommen, dazu Coaches-Sektion, Footer-Links (Vergleiche, Ehrlich geschätzt, Partner werden), Feedback-Copy und „Fielen GmbH" aus der DSGVO-Sektion entfernt. Ersetzt die Repo-Version 1:1.

## Magazin „Ehrlich geschätzt" (Blog-System)
- `ehrlich-geschaetzt.html` — Übersichtsseite. Neue Artikel-Karte oben ins Grid einfügen (Kommentar im Quelltext zeigt, was zu ersetzen ist).
- `beitraege/_vorlage.html` — Artikel-Vorlage. Neuen Artikel anlegen in 3 Schritten:
  1. Datei kopieren → `beitraege/mein-thema.html` (Kleinbuchstaben, Bindestriche)
  2. Die 4 markierten Stellen füllen (▼-Kommentare): Title/Description, Kopfzeile, Inhalt, CTA. Im Inhalt einfach `<p>`, `<h2>`, `<ul>` schreiben — Aussehen kommt automatisch. Bausteine „Spannen-Box"/„Merksatz" nutzen oder löschen.
  3. Karte auf `ehrlich-geschaetzt.html` eintragen (neueste zuerst).
- `beitraege/doener-kalorien-ehrlich-geschaetzt.html` — erster Artikel, dient auch als ausgefülltes Beispiel.
