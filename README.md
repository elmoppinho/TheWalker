# SEELENWANDERER – 16-Bit Fan Edition (spielbare Ausgabe)

Fünf miteinander verbundene Minispiele in einer einzigen HTML-Datei: Kerker, Arena, Boxring, Kart-Piste und ein geheimes Turm-Kapitel. Grafik und Charaktere sind eigenständig gestaltet.

## Wichtig: Auf dem iPhone wirklich spielen

Die Dateivorschau in der ChatGPT- oder Dateien-App ist **kein vollwertiger Webbrowser**. Sie kann JavaScript-Spiele nur als Datei anzeigen oder die Ausführung verhindern. In dieser Vorschau funktioniert das Spiel dann nicht, selbst wenn die HTML-Datei korrekt ist.

**Der zuverlässigste Weg ist GitHub Pages:**

1. Den ZIP-Ordner entpacken. Er enthält `index.html` und `.nojekyll`.
2. Auf github.com ein Repository für das Spiel öffnen bzw. erstellen (für GitHub Pages ggf. öffentlich).
3. Die Datei `index.html` und `.nojekyll` in das oberste Verzeichnis dieses Repositories hochladen und committen.
4. Im Repository unter **Settings → Pages** den Punkt **Deploy from a branch** auswählen. Branch: `main`; Ordner: `/(root)`; danach speichern.
5. Die von GitHub Pages angezeigte Adresse **in Safari** öffnen. Üblich ist `https://BENUTZERNAME.github.io/REPOSITORY/`.
6. Optional in Safari **Teilen → Zum Home-Bildschirm** wählen.

Die Webseite benötigt keine weiteren Grafik-, Sound- oder Fontdateien und keine Netzwerkanfragen nach dem Laden.

## Steuerung

| Kapitel | Bewegung | A | B |
| --- | --- | --- | --- |
| 1 Kerker | D-Pad, Schussrichtung = Laufrichtung | schießen | – |
| 2 Arena | links/rechts, hoch = Sprung | Schlag | blocken |
| 3 Boxring | links/rechts ausweichen | Schlag | Deckung |
| 4 Kart-Piste | links/rechts lenken, Gas automatisch | schneller beschleunigen | bremsen |
| 5 Dämmerturm | D-Pad | Schraubenschlüssel | – |

Tastatur: Pfeiltasten; `X` für A, `C` für B; `P` für Pause. Das Spiel lässt sich oben zurücksetzen und die Kapitel 1–4 lassen sich direkt anwählen.

### Der geheime Weg

Wer kurz vor Rennende als Erster führt, ganz anhält, alle fünf Kontrahenten passieren lässt und schließlich als Letzter die Ziellinie überquert, erreicht eine alternative Geschichte und den Dämmerturm. Für das Anhalten **B gedrückt halten**.

## Technik

- Einzelne, eigenständige HTML5-Canvas-Datei mit JavaScript, CSS und integrierten Sprites.
- Browserdarstellung mit Logik auf 60 Hz; reduzierter Zeichnungsfrequenz auf Geräten mit Touch-Eingabe.
- Getestet mit Chromium-Browser-Simulationen im Smartphone-Hochformat, im Querformat und auf einem Desktop. Auf einem echten iPhone nicht geprüft.
- Die Kapitel sowie der alternative Renn-Ausgang wurden mit automatisierten Tests überprüft.

## Hinweis zur Grafik

Die Spiele und Figuren sind eigene Fan-Hommagen an verschiedene Videospielgenres und an die Bildsprache früher Konsolenspiele. Es werden keine Originalsprites, Logos oder Spieldateien der Vorbilder eingebunden.
