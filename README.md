# Mathe & Statistik – Lernapp

Lernapp für das Modul „Mathematik und Statistik“ (BA, Frankfurt School).
Bezeichnungen wie in Skript und Formelsammlung.

- 3 Bereiche, 19 Unterthemen mit Lernzettel
- 60 Aufgabentypen mit Zufallszahlen (Zahleneingabe, Terme, Multiple Choice)
- Lösungsweg zu jeder Aufgabe
- Tests über mehrere Themen und Bereiche hinweg
- Tabelle der Standardnormalverteilung
- läuft offline, alles in einer Datei (`index.html`), Fortschritt lokal im Browser.

## Aufbau
- `index.html` – fertige App (wird aus `src/` gebaut)
- `src/` – Quellcode: `content.js` (Lernzettel), `gens.js` (Aufgaben), `ui.js` (Oberfläche)
- `build.js` – baut `index.html` (`node build.js`, benötigt KaTeX)
