# Lernprogramme — Rechtsfachmann HF

Interaktive, self-contained HTML-Lernprogramme zum Lehrgang dipl. Rechtsfachmann HF
(Semester 3). Jede Datei läuft ohne Installation und ohne
Internet — Doppelklick genügt, der Fortschritt wird im Browser gespeichert.

Einstiegspunkt ist [`index.html`](index.html) — eine Startseite, die alle vier Programme verlinkt.

## Inhalt

| Datei | Fach | Umfang |
|---|---|---|
| [`programme/verwaltungsrecht-i.html`](programme/verwaltungsrecht-i.html) | Verwaltungsrecht I | 100 Aufgaben in 14 Themen |
| [`programme/erbrecht.html`](programme/erbrecht.html) | Erbrecht (Teil 1 + 2) | 83 Übungen in 11 Stufen |
| [`programme/erwachsenenschutzrecht.html`](programme/erwachsenenschutzrecht.html) | Erwachsenenschutzrecht | 77 Fragen in 11 Themen |
| [`programme/gueterrecht.html`](programme/gueterrecht.html) | Güterrechtliche Auseinandersetzung | 20 Fälle in 6 Phasen |

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
