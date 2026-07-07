# Übergabe: Vergleichsseiten + Partnerseite

Alle Dateien ins Root des Calwatch-Web-Repos. `support.js` nur nötig, falls noch nicht vorhanden.

- `vergleiche.html` + 5 × `calwatch-oder-*.html` — SEO-Vergleichsseiten. Footer der index.html sollte auf `vergleiche.html` verlinken. Disclaimer am Seitenende nicht entfernen (rechtliche Absicherung); Preisangaben halbjährlich prüfen.
- `calwatch-scouts.html` — Partnerseite, jetzt mit Kontaktformular am Ende (#start): Name, E-Mail, Kategorie, Freitext. Der Button öffnet eine fertige E-Mail an **partner@calwatch.io** (mailto — kein Backend nötig). Adresse ggf. im HTML + Script anpassen (2 Stellen: `partner@calwatch.io`). Später einfach gegen echten Form-Endpoint tauschbar.
- `index.html` — mit Repo-Stand (4de7cef) abgeglichen: eure Hero-Preiszeile („4,90 € monatlich kündbar oder 49 € jährlich") ist übernommen, dazu Coaches-Sektion, Footer-Links (Vergleiche, Partner werden), Feedback-Copy und „Fielen GmbH" aus der DSGVO-Sektion entfernt. Ersetzt die Repo-Version 1:1.
