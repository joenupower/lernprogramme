# Lernprogramme — Rechtsfachmann HF

Interaktive, self-contained HTML-Lernprogramme zum Lehrgang dipl. Rechtsfachmann HF
(Semester 3). Jede Datei läuft ohne Installation und ohne
Internet — Doppelklick genügt, der Fortschritt wird im Browser gespeichert.

Einstiegspunkt ist [`index.html`](index.html) — eine Startseite, die alle fünf Programme verlinkt.

## Inhalt

| Datei | Fach | Umfang |
|---|---|---|
| [`programme/verwaltungsrecht-i.html`](programme/verwaltungsrecht-i.html) | Verwaltungsrecht I | 100 Aufgaben in 14 Themen |
| [`programme/erbrecht.html`](programme/erbrecht.html) | Erbrecht (Teil 1 + 2) | 83 Übungen in 11 Stufen |
| [`programme/erwachsenenschutzrecht.html`](programme/erwachsenenschutzrecht.html) | Erwachsenenschutzrecht | 77 Fragen in 11 Themen |
| [`programme/gueterrecht.html`](programme/gueterrecht.html) | Güterrechtliche Auseinandersetzung | 20 Fälle in 6 Phasen |
| [`programme/schkg-fristarten.html`](programme/schkg-fristarten.html) | SchKG — Fristarten | 34 Artikel, 4 Fristarten |

## Auf dem Handy

Jedes Programm ist zusätzlich als private Seite veröffentlicht. Im mobilen Browser öffnen,
dann «Zum Home-Bildschirm» — damit startet es wie eine App im Vollbild.

| Programm | Link |
|---|---|
| Verwaltungsrecht I | https://claude.ai/code/artifact/439a30cf-7780-43e4-9545-3f67b4ac4ff2 |
| Erbrecht | https://claude.ai/code/artifact/fbb6690f-fdc0-4cb7-83cb-9d2425504f9b |
| Erwachsenenschutzrecht | https://claude.ai/code/artifact/9f95f9fd-e099-46f9-9d80-3284e0406f90 |
| Güterrecht | https://claude.ai/code/artifact/60f9e1a9-e023-44a4-9c27-f3bb06c8bb5f |
| SchKG — Fristarten | https://claude.ai/code/artifact/b688e725-ee8e-4f7e-9a41-c4ee0cc6c064 |

Die Seiten sind privat und nur im angemeldeten Zustand sichtbar. Der Fortschritt wird pro
Gerät und Browser gespeichert; Handy und Computer zählen also getrennt.

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

Die Aufgaben stützen sich auf Kursunterlagen (Dozenten-Scripts, Übungsblätter mit
Musterlösungen). Dieses Repository ist deshalb privat
und ausschliesslich für den persönlichen Gebrauch bestimmt.
