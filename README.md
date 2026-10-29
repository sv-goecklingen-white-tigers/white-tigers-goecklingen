# White Tigers Göcklingen

Webseite der White Tigers, der Dartabteilung des SV Rot-Weiß Göcklingen 1946 e.V.
Zwei Mannschaften in der Badischen Dartliga: Team 1 in der Bezirksoberliga 1, Team 2 in der Kreisbezirksliga 1.

Die Seite ist eine einzelne `index.html` ohne Build-Schritt, Bilder liegen in `assets/`.

## Daten aktualisieren

Alle Ligadaten stehen oben im `<script>`-Block der `index.html`:

- `STAND` – Datum des Datenstands
- `TABLES` – Tabellen beider Ligen (von badischedartliga.de abschreiben)
- `SCHEDULE` – Spielpläne; nach einem Spiel das Ergebnis `[wir, gegner]` und die Spielbericht-ID eintragen
- `CUP` – BDL-Pokal
- `GAMES` – die einzelnen Spielberichte; daraus berechnet die Seite Kader und Spielerstatistik

Quellen: [Bezirksoberliga 1](https://www.badischedartliga.de/bzo1) · [Kreisbezirksliga 1](https://www.badischedartliga.de/kbz1) · [Pokal 2026/27](https://www.badischedartliga.de/index.php?id=pokal-2627)
