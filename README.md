# Japan Reiseplaner als Web-App veröffentlichen

Inhalt dieses Ordners: index.html, manifest.webmanifest, sw.js, icon-180/192/512.png.
Alle Dateien müssen zusammen im selben Ordner liegen.

## Weg 1: Netlify Drop (am einfachsten, ca. 2 Minuten)
1. Auf https://app.netlify.com/drop gehen und ein Gratis-Konto anlegen.
2. Den ganzen Ordner "reiseplaner-app" (oder die entpackte ZIP) ins Fenster ziehen.
3. Netlify zeigt einen Link wie https://zufaelliger-name.netlify.app. Optional unter "Site configuration" den Namen ändern.
4. Link per WhatsApp verschicken.

## Weg 2: GitHub Pages
1. Auf github.com ein Gratis-Konto anlegen, "New repository" (öffentlich), z. B. "japan-planer".
2. "Add file" > "Upload files", alle Dateien hochladen, "Commit".
3. Settings > Pages > Branch "main", Ordner "/ (root)" > Save.
4. Nach 1 bis 2 Minuten ist die App unter https://DEINNAME.github.io/japan-planer/ erreichbar.

## Aufs Handy installieren
- iPhone (Safari): Link öffnen > Teilen > "Zum Home-Bildschirm".
- Android (Chrome): Link öffnen > Menü > "App installieren" bzw. "Zum Startbildschirm".

## Wichtig
- Notizen, Bilder und Pläne liegen nur auf dem Gerät, auf dem sie eingegeben wurden. Jedes Handy hat seine eigene Kopie.
- Die Seite ist öffentlich erreichbar, wer den Link kennt, kann sie öffnen. Persönliche Daten stehen aber nicht darin, die gibt jeder nur lokal ein.
- Kartenkacheln kommen von OpenStreetMap (und Esri für Satellit). Die App merkt sich nur Kacheln, die ihr einmal angesehen habt. Bitte nicht massenhaft Gebiete vorladen.
- Leaflet wird von unpkg.com geladen und beim ersten Öffnen für offline zwischengespeichert.
