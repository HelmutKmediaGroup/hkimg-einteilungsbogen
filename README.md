# HKIMG Einteilungsbogen

Ihr individueller Nutzenrechner

Web-App für Druckereien: Nutzenberechnung, Laufrichtung, Farbigkeit inkl. Sonderfarben, Ränder und Greiferrand, Umschlag mit Rückenbreite (Bundleimung), 4-fach-Rillung, Kopf-, Fuß- und Frontbeschnitt sowie Gewichtsberechnung. Der Einteilungsbogen wird als bemaßtes PDF (A4 quer) exportiert.

Die App ist eine installierbare Web-App (PWA): Sie läuft auf Android, iPhone/iPad und am Desktop, auch ohne Internet. Bei jedem Start beginnt sie mit den Standardwerten; es wird nichts im Browser gespeichert.

## Installieren

- **Android (Chrome):** App-Adresse öffnen → „App installieren“
- **iPhone/iPad (Safari):** App-Adresse öffnen → „Teilen“ → „Zum Home-Bildschirm“
- **Windows/Mac (Chrome, Edge):** App-Adresse öffnen → Installieren-Symbol in der Adressleiste

## Online stellen

- **GitHub Pages:** Settings → Pages → Branch `main`, Ordner `/ (root)` → Save.
  Danach erreichbar unter `https://helmutkmediagroup.github.io/hkimg-einteilungsbogen/`
- **Lovable:** alle Dateien nach `public/einteilungsbogen/` kopieren und mit `/einteilungsbogen/index.html` verlinken.

## Dateien

| Datei | Zweck |
|---|---|
| `index.html` | die komplette App (Schriften und PDF-Bibliotheken eingebettet) |
| `manifest.webmanifest` | App-Name, Farben, Symbole |
| `sw.js` | Offline-Cache, lädt Updates automatisch |
| `icon-*.png`, `apple-touch-icon.png`, `favicon-64.png` | App-Symbole |
| `.nojekyll` | verhindert die Jekyll-Verarbeitung bei GitHub Pages |

## Update einspielen

Neue Dateien über die alten kopieren und committen. Installierte Apps laden das Update beim nächsten Start mit Internetverbindung.

Lizenzen eingebetteter Komponenten: jsPDF und svg2pdf.js (MIT), Montserrat, Inter und IBM Plex Mono (SIL Open Font License 1.1).
