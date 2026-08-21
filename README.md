# Lernprogramme — Rechtsfachmann HF

Interaktive, self-contained HTML-Lernprogramme zum Lehrgang dipl. Rechtsfachmann HF
(Semester 3). Jede Datei läuft ohne Installation und ohne
Internet — Doppelklick genügt, der Fortschritt wird im Browser gespeichert.

Einstiegspunkt ist [`index.html`](index.html) — eine Startseite, die alle sieben Programme verlinkt.

## Inhalt

| Datei | Fach | Umfang |
|---|---|---|
| [`programme/verwaltungsrecht-i.html`](programme/verwaltungsrecht-i.html) | Verwaltungsrecht I | 100 Aufgaben in 14 Themen |
| [`programme/erbrecht.html`](programme/erbrecht.html) | Erbrecht (Teil 1 + 2) | 83 Übungen in 11 Stufen |
| [`programme/erwachsenenschutzrecht.html`](programme/erwachsenenschutzrecht.html) | Erwachsenenschutzrecht | 77 Fragen in 11 Themen |
| [`programme/gueterrecht.html`](programme/gueterrecht.html) | Güterrechtliche Auseinandersetzung | 20 Fälle in 6 Phasen |
| [`programme/mietrecht-falltrainer.html`](programme/mietrecht-falltrainer.html) | Mietrecht (OR 253–274) | 50 Fälle in 16 Themenblöcken |
| [`programme/schkg-fristenberechnung.html`](programme/schkg-fristenberechnung.html) | SchKG — Fristenberechnung | 50 Aufgaben im Kalender |
| [`programme/schkg-fristarten.html`](programme/schkg-fristarten.html) | SchKG — Fristarten | 34 Artikel, 4 Fristarten |

## Auf dem Handy

Alle Programme laufen unter **https://joenupower.github.io/lernprogramme/** — ohne Anmeldung,
in jedem Browser. Im mobilen Browser öffnen, dann «Zum Home-Bildschirm»: Damit startet die
Sammlung wie eine App im Vollbild.

Direktlinks:

| Programm | Adresse |
|---|---|
| Güterrecht | https://joenupower.github.io/lernprogramme/programme/gueterrecht.html |
| Erbrecht | https://joenupower.github.io/lernprogramme/programme/erbrecht.html |
| Erwachsenenschutzrecht | https://joenupower.github.io/lernprogramme/programme/erwachsenenschutzrecht.html |
| Mietrecht | https://joenupower.github.io/lernprogramme/programme/mietrecht-falltrainer.html |
| SchKG — Fristenberechnung | https://joenupower.github.io/lernprogramme/programme/schkg-fristenberechnung.html |
| SchKG — Fristarten | https://joenupower.github.io/lernprogramme/programme/schkg-fristarten.html |
| Verwaltungsrecht I | https://joenupower.github.io/lernprogramme/programme/verwaltungsrecht-i.html |

Der Fortschritt wird pro Gerät und Browser gespeichert; Handy und Computer zählen getrennt.

## Aufbau der Programme

Alle vier folgen demselben Muster: eine einzige HTML-Datei mit CSS und JavaScript
inline, keine externen Abhängigkeiten. Die Aufgaben stehen deklarativ in einem Array
(`FRAGEN` bzw. `UEBUNGEN` / `CASES`), die Anzeige-Logik ist davon getrennt.

Gemeinsame Merkmale:

- Aufgaben mit aufsteigendem Schwierigkeitsgrad innerhalb jedes Themas
- Sofort-Feedback, Erklärung mit Gesetzesartikeln zu jeder Aufgabe
- Fortschritt in `localStorage`, unterschieden nach «selbständig gelöst» und
  «mit Lösungshilfe gelöst»
- Spickzettel mit den Kurstabellen
- Antwortoptionen werden bei jedem Aufruf gemischt

## Bearbeiten

Aufgaben ergänzt man im Daten-Array der jeweiligen Datei; neue Gesetzesartikel
gehören zuerst ins `GESETZ`-Dictionary (Grundlage für die Tooltips bzw. die
Anzeige beim Antippen).

## Hinweis zu den Inhalten

Die Aufgaben sind für das eigene Lernen entstanden und stützen sich auf Kursunterlagen und
Übungsblätter mit Musterlösungen. Wer sie nutzt, sollte die Lösungen an der eigenen
Vorlesung und am geltenden Gesetzestext gegenprüfen — Stand und Methodik richten sich nach
dem jeweiligen Kurs.
