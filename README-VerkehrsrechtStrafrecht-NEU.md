# ⚖️ FL-VerkehrsrechtStrafrecht - Verkehrsrecht & Strafrecht Editor (Erweitert)

**Fahrlehrer-Ausbildung FL-BE_07/25**  
Justin Lee Probis

---

## 📚 Über dieses Repository

Dieses Repository enthält die Daten für den **Verkehrsrecht & Strafrecht Editor** - ein professionelles Werkzeug zur systematischen Aufbereitung aller relevanten rechtlichen Grundlagen für die Fahrlehrer-Ausbildung.

Der Editor ermöglicht die strukturierte Erfassung von Gesetzestexten zu Haftung, Versicherung, Bußgeldern, Strafen, Personenbeförderung und deren Synchronisation über GitHub.

---

## 📂 Repository-Struktur

```
FL-VerkehrsrechtStrafrecht/
├── README.md       (diese Datei - Projektbeschreibung)
└── data.json       (Verkehrsrecht/Strafrecht-Daten, automatisch synchronisiert vom Editor)
```

---

## 📋 Enthaltene Gesetze

Dieses Tool vereint alle wichtigen rechtlichen Grundlagen in einem Editor:

- **PflVG** - Pflichtversicherungsgesetz
- **BGB** - Bürgerliches Gesetzbuch (verkehrsrelevante Teile)
- **OWiG** - Ordnungswidrigkeitengesetz
- **BKatV** - Bußgeldkatalog-Verordnung
- **StGB** - Strafgesetzbuch (verkehrsrelevante Delikte)
- **PBefG** - Personenbeförderungsgesetz
- **Sonstiges** - Platzhalter für weitere Vorschriften

---

## 🔄 Daten-Synchronisation

Die Datei `data.json` wird **automatisch** vom Verkehrsrecht & Strafrecht Editor synchronisiert:

- ✅ Jedes Speichern im Editor aktualisiert diese Datei
- ✅ Änderungen werden mit Zeitstempel versioniert
- ✅ Team-Kollaboration möglich (mehrere Nutzer, ein Repository)

**⚠️ WICHTIG:** Die `data.json` sollte **nicht manuell bearbeitet** werden!  
Alle Änderungen bitte nur über den Verkehrsrecht & Strafrecht Editor vornehmen.

---

## 🛠️ Verwendung

### 1. Repository-Setup (einmalig)
- Repository erstellt: ✅ `710Deckel/FL-VerkehrsrechtStrafrecht`
- README.md hochgeladen: ✅

### 2. Editor-Verwendung
- HTML-Datei lokal öffnen (`verkehrsrecht-strafrecht-editor.html`)
- GitHub Token eingeben (einmalig, gleicher Token wie andere Tools!)
- Gesetz aus Dropdown auswählen (PflVG, BGB, OWiG, BKatV, StGB, PBefG, Sonstiges)
- Paragraphen hinzufügen und speichern
- Automatische Synchronisation erfolgt

### 3. Token-Anforderungen
Der verwendete Token benötigt folgende Berechtigungen:
- ✅ `repo` (Full control of private repositories)

**Hinweis:** Du kannst denselben Token für alle Fahrlehrer-Tools verwenden!

---

## 📋 Datenstruktur

Die `data.json` enthält alle Paragraphen aus allen Gesetzen im folgenden Format:

```json
{
  "paragraphen": [
    {
      "id": "timestamp",
      "gesetz": "PflVG",
      "nummer": "§ 1",
      "titel": "Versicherungspflicht",
      "gesetzestext": "...",
      "quelle": "https://...",
      "praxisbeispiele": [
        {
          "titel": "Beispiel",
          "klasse": "ALLE",
          "beschreibung": "...",
          "wichtigkeit": "CRITICAL"
        }
      ]
    }
  ]
}
```

---

## 🎯 Features des Editors

- **2-Spalten-Layout:** Gesetzestext | Praxisbeispiele
- **Gesetz-Auswahl:** Dropdown für 7 verschiedene Gesetze
- **GitHub Auto-Sync:** Automatische Synchronisation
- **Template-System:** Vordefinierte Beispiele für Haftung, Bußgelder, Strafen
- **Badge-System:** CRITICAL (rot) | HIGH (orange) | BANAL (grün)
- **PDF-Export:** Professionelle Druckausgabe
- **Import/Export:** JSON-Backup-System
- **Keyboard Shortcuts:** Strg+S zum Speichern
- **Amber Theme:** Speziell für Rechtsthemen

---

## ⚖️ Wichtige Bereiche

Der Editor deckt alle wichtigen rechtlichen Bereiche ab:

**PflVG (Pflichtversicherungsgesetz):**
- § 1 - Versicherungspflicht
- § 6 - Deckungssummen
- § 117 - Auskunftspflichten

**BGB (Bürgerliches Gesetzbuch):**
- § 823 - Schadensersatzpflicht
- § 254 - Mitverschulden
- § 831 - Haftung für Verrichtungsgehilfen

**OWiG (Ordnungswidrigkeitengesetz):**
- § 1 - Begriffsbestimmung
- § 24 - Vorsatz und Fahrlässigkeit
- § 47 - Bußgeld

**BKatV (Bußgeldkatalog-Verordnung):**
- Tatbestände und Bußgelder
- Punktesystem
- Fahrverbote

**StGB (Strafgesetzbuch):**
- § 142 - Unerlaubtes Entfernen vom Unfallort
- § 222 - Fahrlässige Tötung
- § 315c - Gefährdung des Straßenverkehrs
- § 316 - Trunkenheit im Verkehr

**PBefG (Personenbeförderungsgesetz):**
- Genehmigungspflichten
- Taxi- und Mietwagenverkehr
- Linienverkehr
- Schulbusverkehr

---

## 🔗 Weitere Fahrlehrer-Tools

Dieses Repository ist Teil einer systematischen Tool-Suite für die Fahrlehrer-Ausbildung:

- [📘 FL-StVO](https://github.com/710Deckel/stvo-teleprompter) - StVO Teleprompter mit Erläuterungen
- [🚛 FL-FPersV-EG-VO](https://github.com/710Deckel/FL-FPersV-EG-VO) - Fahrpersonalverordnung & EU-Verordnung
- [⚖️ FL-StVG](https://github.com/710Deckel/FL-StVG) - Straßenverkehrsgesetz
- [🔧 FL-StVZO](https://github.com/710Deckel/FL-StVZO) - Straßenverkehrs-Zulassungs-Ordnung
- [📋 FL-FeV](https://github.com/710Deckel/FL-FeV) - Fahrerlaubnis-Verordnung
- [🚗 FL-FZV](https://github.com/710Deckel/FL-FZV) - Fahrzeug-Zulassungsverordnung
- [👨‍🏫 FL-FahrlehrerGesetze](https://github.com/710Deckel/FL-FahrlehrerGesetze) - Fahrlehrer-Gesetze
- [⚖️ FL-VerkehrsrechtStrafrecht](https://github.com/710Deckel/FL-VerkehrsrechtStrafrecht) - Verkehrsrecht & Strafrecht (dieses Repository - ERWEITERT)
- [📝 FL-Pruefungsrichtlinie](https://github.com/710Deckel/FL-Pruefungsrichtlinie) - Prüfungsrichtlinie Kfz
- [📚 FL-SonstigeVerkehrsvorschriften](https://github.com/710Deckel/FL-SonstigeVerkehrsvorschriften) - Sonstige Verkehrsvorschriften

---

## 📝 Lizenz & Verwendung

**Projekt:** Fahrlehrer-Ausbildung FL-BE_07/25  
**Ersteller:** Justin Lee Probis  
**Zweck:** Ausbildung und Podcast "Fahrlehrer Inside"

Dieses Tool und die Daten sind für **Ausbildungszwecke** erstellt.

---

## 📞 Kontakt & Feedback

Bei Fragen, Problemen oder Verbesserungsvorschlägen:
- GitHub Issues in diesem Repository
- Feedback über das Tool (Thumbs Down Button)

---

**Erstellt mit ❤️ für die Fahrlehrer-Ausbildung**

*Letzte Aktualisierung: Dezember 2024*
