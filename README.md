# 🗺️ Atlasinfo Manager 2.0.0

Ein professionelles Desktop-Tool zur Verwaltung von Metin2 Map-Koordinaten mit moderner Benutzeroberfläche.

## 🌟 Features

- **Visuelle Map-Darstellung**: Alle Maps werden als farbige Rechtecke auf einem Grid angezeigt
- **Drag & Drop**: Verschieben Sie Maps einfach per Mausklick
- **Kollisionserkennung**: Automatische Erkennung und Markierung überlappender Maps
- **Zoom & Navigation**: Vollständige Zoom-Funktionen und Navigation
- **Modernes Design**: Helles, professionelles Theme
- **Datei-Management**: Laden und Speichern von `atlasinfo.txt` Dateien
- **Professionelle Oberfläche**: Intuitive Benutzeroberfläche mit Menüs und Shortcuts

## 🚀 Schnellstart

1. Starten Sie die Anwendung durch Doppelklick auf `Atlasinfo Manager.exe`
2. Laden Sie Ihre `atlasinfo.txt` Datei über "Atlasinfo laden" oder `Strg+O`
3. Die Maps werden automatisch visualisiert und alle Maps werden angezeigt

## 📁 Systemanforderungen

- **Windows**: 10/11 (64-bit)
- **RAM**: Mindestens 4 GB
- **Festplatte**: 100 MB freier Speicherplatz

## 🎮 Verwendung

### Datei laden
1. Klicken Sie auf "Atlasinfo laden" oder verwenden Sie `Strg+O`
2. Wählen Sie Ihre `atlasinfo.txt` Datei aus
3. Die Maps werden automatisch visualisiert

### Maps bearbeiten
- **Auswählen**: Klicken Sie auf eine Map im Canvas oder in der Liste
- **Verschieben**: Ziehen Sie Maps per Drag & Drop mit der linken Maustaste
- **Ansicht verschieben**: Rechtsklick gedrückt halten und ziehen, oder Linksklick auf leeren Bereich
- **Eigenschaften ändern**: Verwenden Sie die Eingabefelder rechts
- **Neue Map**: Klicken Sie auf "Neue Map"
- **Löschen**: Wählen Sie eine Map aus und klicken Sie auf "Map löschen"

### Navigation
- **Zoom**: Mausrad oder Zoom-Buttons (`+` / `-`)
- **Zoom zurücksetzen**: `Strg+0` oder "Reset" Button
- **Alle anzeigen**: `Strg+F` oder "Alle Maps anzeigen"
- **Ansicht verschieben**: 
  - Rechtsklick + Ziehen (funktioniert überall)
  - Linksklick auf leeren Bereich + Ziehen
  - Tastatur: `W/A/S/D` oder Pfeiltasten

### Kollisionen
- **Prüfen**: Klicken Sie auf "Kollisionen prüfen" oder `Strg+C`
- **Visuelle Anzeige**: Kollidierende Maps werden rot markiert
- **Erweiterte Prüfung**: Prüft auf:
  - Überlappende Maps (gleiche Koordinaten)
  - Maps mit identischen Base-Koordinaten
  - Formatierungsprobleme in der Datei (z.B. Leerzeichen statt TABs)

### Suche
- Verwenden Sie das Suchfeld in der Map-Liste
- Gefundene Maps werden grün markiert
- Kollidierende Maps werden rot markiert

## 🔄 Atlasinfo-Dateiformat

Die `atlasinfo.txt` Datei muss folgendes Format haben:

```
map_name	base_x	base_y	size_x	size_y
map_a1	    256000	0	    4	    4
map_b1	    0	    256000	4	    4
```

**Wichtig**: Alle Werte müssen durch **TAB-Trennzeichen** getrennt sein, nicht durch Leerzeichen!

- **map_name**: Name der Map
- **base_x/base_y**: Startkoordinaten (in Metin2-Einheiten)
- **size_x/size_y**: Größe in Map-Einheiten (1 Einheit = 25600 Pixel)

## ⌨️ Tastenkürzel

| Tastenkürzel | Funktion |
|-------------|----------|
| `Strg+O` | Datei öffnen |
| `Strg+S` | Datei speichern |
| `Strg+Shift+S` | Speichern unter |
| `Strg+C` | Kollisionen prüfen |
| `Strg+F` | Alle Maps anzeigen |
| `Strg++` | Zoom vergrößern |
| `Strg+-` | Zoom verkleinern |
| `Strg+0` | Zoom zurücksetzen |
| `W/A/S/D` | Ansicht verschieben |
| `Pfeiltasten` | Ansicht verschieben |

## 🎨 Farben und Markierungen

- **Blau**: Normale Maps
- **Gelb**: Ausgewählte Map
- **Rot**: Maps mit Kollisionen
- **Grün**: Maps die in der Suche gefunden wurden

## ⚠️ Wichtige Hinweise

- **TAB-Trennzeichen**: Stellen Sie sicher, dass Ihre `atlasinfo.txt` Datei TAB-Trennzeichen verwendet, nicht Leerzeichen
- **Backup**: Erstellen Sie vor größeren Änderungen ein Backup Ihrer Datei
- **Kollisionen**: Prüfen Sie regelmäßig auf Kollisionen, um Probleme zu vermeiden
- **Speichern**: Vergessen Sie nicht, Ihre Änderungen zu speichern (`Strg+S`)

## 🐛 Fehlerbehebung

### Datei kann nicht geladen werden
- Überprüfen Sie das Dateiformat - jede Zeile sollte: `name\tbase_x\tbase_y\tsize_x\tsize_y` enthalten
- Stellen Sie sicher, dass TAB-Trennzeichen verwendet werden, nicht Leerzeichen

### Maps werden nicht angezeigt
- Verwenden Sie "Alle Maps anzeigen" (`Strg+F`)
- Prüfen Sie den Zoom-Level

### Kollisionswarnung
- Klicken Sie auf "Kollisionen prüfen" für Details
- Rote Maps haben Kollisionen und sollten überprüft werden

## 📝 Version

**Version 2.0.0**

## 🤝 Support

Bei Fragen oder Problemen besuchen Sie: https://github.com/ABCXX9X

---

**Entwickelt mit ❤️ für die Metin2-Community**

