# Routina

Web-App zum täglichen Abhaken von Gewohnheiten. Läuft im Browser auf Handy und PC und lässt sich auf den Homescreen legen.

**Live:** https://nailitnow.netlify.app/

## Funktionen

- Gewohnheiten abhaken, entweder als einfacher Haken oder mit Zielwert (z. B. 3 Liter Wasser, 10.000 Schritte)
- Übersicht nach Woche, Monat und Jahr
- Statistik mit Erfolgsquote, Serien und Meilensteinen
- Wochenrückblick
- Dunkles Design

## Aufbau

Die ganze App steckt in einer einzigen Datei: `index.html` (HTML, CSS und JavaScript). Es gibt keinen Build-Schritt und keine Abhängigkeiten.
Die Daten werden im Browser gespeichert (`localStorage`), also nur auf dem jeweiligen Gerät.

## Lokal starten

`index.html` einfach im Browser öffnen.

## Veröffentlichen

Auf Netlify: Projekt mit diesem Repository verbinden (Build-Befehl leer lassen, Publish-Ordner `/`). Danach geht jede Änderung auf GitHub automatisch online.
