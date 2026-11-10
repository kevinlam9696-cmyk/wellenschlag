# Wellenschlag

Trainings-App für Wasser-Rudergeräte mit Bluetooth (FTMS), entwickelt für das JASPORT M1.
Läuft komplett im Browser (Chrome auf Android oder am Computer). Alle Trainingsdaten bleiben auf deinem Gerät.

## Als Web-App auf GitHub Pages veröffentlichen

1. Auf github.com ein neues Repository anlegen, zum Beispiel `wellenschlag`. „Public“ wählen.
2. Den Inhalt dieses Ordners hochladen: „Add file“ → „Upload files“, alle Dateien und den Ordner `icons` hineinziehen, dann „Commit changes“.
   `index.html` muss direkt im Hauptordner liegen.
3. Im Repository „Settings“ → „Pages“ öffnen. Unter „Build and deployment“ bei „Source“ „Deploy from a branch“ wählen,
   als Branch `main` und Ordner `/ (root)`, dann „Save“.
4. Nach ein bis zwei Minuten ist die App erreichbar unter `https://DEIN-NAME.github.io/wellenschlag/`.
5. Die Adresse auf dem Handy in Chrome öffnen und über „Werte“ → „Gerät“ → „Wellenschlag installieren“
   (oder Chrome-Menü ⋮ → „App installieren“) auf den Startbildschirm legen.

## Daten aus der bisherigen Datei mitnehmen

Der Browser speichert Daten getrennt pro Adresse. Die neue Adresse auf GitHub startet deshalb leer.

1. In der bisherigen App: „Erfolge“ → „Trainingsdaten exportieren und importieren“ → „Sicherung als Datei“.
2. In der neuen App auf GitHub: an derselben Stelle „Datei auswählen“ und die Sicherungsdatei wählen, dann „Übernehmen“.

Abzeichen, Muscheln, Boote und alle Einheiten sind danach wieder da.

## Updates

Neue Versionen einfach als `index.html` im Repository ersetzen („Add file“ → „Upload files“).
Die App lädt beim nächsten Öffnen mit Internet automatisch die neue Version. Ohne Internet läuft die zuletzt geladene.

## Dateien

- `index.html`: die komplette App
- `manifest.webmanifest`: Name, Farben und Symbole für die Installation
- `sw.js`: sorgt dafür, dass die App auch offline startet
- `icons/`: Logo als SVG und PNG in allen nötigen Größen
