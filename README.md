# DateGlas 🫙❤️

[🌐 Live-Demo ansehen](https://tangerine-marigold-5f64db.netlify.app/)

Ein süßes Date-Ideen-Glas als Progressive Web App (PWA). Tippe auf das Glas, schüttle es und erhalte eine zufällige Idee für ein Date mit deinem Partner oder deiner Partnerin.

## Funktionen

- 🎁 Interaktives Glas mit Schüttel-Animation
- 💡 Über 35 vorgenerierte Date-Ideen (Picknick, Kochen, Wandern, Spielen und mehr)
- 📱 Als PWA installierbar – läuft auch offline auf dem Smartphone
- 🎨 Warmes, verspieltes Design mit Schleifen-Bow und Herz-Animation

## Nutzung

Öffne einfach die `index.html` im Browser. Ein Klick auf das Glas zeigt eine zufällige Date-Idee an. Nochmal klicken (oder auf den Hintergrund) blendet die Karte wieder aus.

## Installation (lokal)

Da es sich um eine statische Web-App handelt, benötigst du keinen Build-Schritt:

```bash
# Einfach die Dateien servieren, z. B. mit Python:
python -m http.server 8000
```

Anschließend `http://localhost:8000` im Browser öffnen.

## Als PWA installieren

1. Die App über einen lokalen Server (siehe oben) oder Webspace bereitstellen.
2. Im Browser (Chrome/Edge/Safari) über „Zum Startbildschirm hinzufügen“ installieren.
3. `manifest.json` und `couple.png` müssen im selben Verzeichnis liegen.

## Dateien

| Datei           | Beschreibung                                              |
|-----------------|-----------------------------------------------------------|
| `index.html`    | Hauptseite mit Glas-Animation und Date-Ideen-Logik       |
| `script.js`     | Alternative Logik zum Ziehen einer Idee (Notiz-Element)  |
| `manifest.json` | PWA-Konfiguration (Name, Icons, Theme-Farbe)              |
| `style.css`     | (leer) Platzhalter für eigenes Styling                    |
| `couple.png`    | Icon/Bild des Paares                                      |
| `import.json`   | Datenimport/Export                                        |

## Eigene Bilder & Ideen

- **Bild austauschen:** Ersetze `couple.png` oder passe den `<img>`-Tag in `index.html` an.
- **Ideen anpassen:** Ergänze Einträge im Array `dateIdeas` in `index.html` bzw. `ideen` in `script.js`.

## Lizenz

Frei nutzbar für private Zwecke.
