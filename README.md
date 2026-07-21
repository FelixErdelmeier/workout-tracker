# Workout Tracker

Ein kleiner, selbstgebauter Workout-Tracker für Push/Pull/Beine-Training mit Satz-für-Satz-Gewichtseingabe, Trainingshistorie und einfachen Gewichtsvorschlägen fürs progressive Training.

> Reines Hobbyprojekt für den Eigenbedarf — kein Anspruch auf Vollständigkeit, Robustheit oder allgemeine Nutzbarkeit. Ich baue daran, wie es mir gerade Spaß macht.

## Nutzung

Einfach [index.html](index.html) öffnen (lokal oder über GitHub Pages). Kein Build, keine Abhängigkeiten — alles läuft clientseitig im Browser, Daten werden per `localStorage` auf dem jeweiligen Gerät gespeichert.

Auf dem iPhone lässt sich die Seite über Safari mit „Zum Home-Bildschirm" wie eine App hinzufügen.

## Daten sichern

Über die Buttons **Backup** / **Wiederherstellen** auf dem Startbildschirm lässt sich die Trainingshistorie als JSON-Datei exportieren bzw. wieder einspielen — sinnvoll vor größeren Umbauten oder als Sicherung, da `localStorage` geräte- und browsergebunden ist.
