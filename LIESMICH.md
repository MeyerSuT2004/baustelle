# Tablet-App „Baustelle“ für die Poliere

Die App läuft im Browser der Android-Tablets (Chrome) und funktioniert auch ohne Netz.
Alle Eingaben bleiben auf dem Tablet, bis der Polier „An das Büro senden“ tippt.
Dieser Ordner enthält nur Programmcode – keine Kunden- oder Baustellendaten.

## Einmalig: App bereitstellen (GitHub Pages)
1. Auf github.com ein Konto für die Firma anlegen (falls noch keins da ist).
2. Neues Repository anlegen, z. B. `baustelle` (öffentlich – es enthält nur Code).
3. Alle Dateien dieses Ordners hochladen („Add file“ → „Upload files“): index.html, sw.js,
   manifest.webmanifest, icon.png, skizze.png.
4. Settings → Pages → Source „Deploy from a branch“, Branch `main`, Ordner `/ (root)` → Save.
5. Nach ein bis zwei Minuten ist die App unter `https://<konto>.github.io/baustelle/` erreichbar.

## Einmalig je Tablet
1. Die Adresse in Chrome öffnen → Menü ⋮ → „Zum Startbildschirm hinzufügen“ / „App installieren“.
2. In der App „Datei aus OneDrive öffnen“ → im Austauschordner `SN-Tablet-Daten.json` wählen.
3. Den eigenen Namen antippen.

## Täglich
- Auftrag antippen (der nächstgelegene steht oben), Kolonne, Tätigkeit, Geräte, ggf. Aufbruch und Skizze.
- „An das Büro senden“ → „OneDrive“ wählen → Austauschordner. Im Büro erscheint die Meldung unter „Eingang Tablets“.
- Neue Aufträge vom Büro: oben „Daten laden“ und die aktuelle `SN-Tablet-Daten.json` öffnen.

## Neue Version der App
Geänderte Dateien im Repository ersetzen. Die Tablets holen sie beim nächsten Start mit Netz automatisch.
