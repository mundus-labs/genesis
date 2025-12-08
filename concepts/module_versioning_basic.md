# Modul: Grundlegendes Modul-Versionierungssystem (Module Versioning)  
ID: module_versioning_basic  
Kategorie: Meta / Versions- & Änderungsmanagement  
Version: 1.0

## Funktion  
Definiert das Versionierungssystem für alle MUNDUS-Module (MMF).  
Stellt sicher, dass Änderungen nachvollziehbar bleiben, KI-Modelle kompatibel arbeiten und Simulationen reproduzierbare Ergebnisse liefern.

## Prinzip  
Jedes Modul besitzt eine **semantische Versionierung** nach dem Schema:

MAJOR.MINOR.PATCH  
(z. B. 1.0, 1.1, 2.0, 2.3.1)

- **MAJOR** – grundlegende Strukturänderungen, Logikänderungen, inkompatible Updates  
- **MINOR** – neue Inhalte, Erweiterungen, nicht-brechende Änderungen  
- **PATCH** – kleine Korrekturen, Schreibfehler, Klarstellungen

Versionen werden im Modulkopf eingetragen und im Wissensgraph historisiert.

## Inputs  
- Moduländerungen  
- neue Informationen  
- Validierungsergebnisse  
- Nutzer-/KI-Feedback  

## Outputs  
- neue Modulversionen  
- Änderungsverlauf  
- kompatible Graphaktualisierungen  
- Versionsvergleich & Historie  

## Voraussetzungen  
- Modul muss gültig sein (Modulvalidierung)  
- Änderung muss dokumentiert werden  
- ID bleibt unverändert  
- alte Versionen dürfen nicht gelöscht werden (nur archiviert)

## Versionierungsregeln  

### 1. MAJOR-Änderung (X.0)  
Notwendig bei:  
- Änderung des Prinzips  
- komplett neuer Mechanismus  
- geänderte technische Bedeutung  
- geänderte Inputs/Outputs  
→ Kann Simulationsergebnisse und Diagramme beeinflussen.

### 2. MINOR-Änderung (0.X)  
Notwendig bei:  
- neue Beispiele  
- zusätzliche Kombinierbarkeit  
- erweiterte Visualisierungen  
- zusätzliche Details  
- Klarstellungen  
→ Kompatibel mit bestehenden Systemen.

### 3. PATCH-Änderung (0.0.X)  
Notwendig bei:  
- Tippfehler  
- Formatkorrekturen  
- kleine textuelle Verbesserungen  

### 4. Deaktivierte Versionen  
Falls ein Modul technisch fehlerhaft war, wird es markiert:

`deprecated: true`  
Mit Grund.

### 5. Historisierung  
Alle Versionen werden gespeichert im:

`genesis/history/`

mit Dateinamen:

`modulename_version.md`

## Abhängigkeiten  
- module_format_basic  
- module_validation_basic  
- knowledge_graph_basic  
- ai_assistant_basic  

## Mechanismus  
1. Änderung am Modul wird vorgeschlagen  
2. Validator prüft Konsistenz & Struktur  
3. Versionierungssystem bestimmt MAJOR/MINOR/PATCH  
4. Modul erhält neue Versionsnummer  
5. Alte Version wird in history/ archiviert  
6. Graph aktualisiert Beziehungen & Metadaten  
7. KI/Sandbox nutzen automatische Versionsauswahl:

   - Standard = neueste kompatible Version  
   - Falls Simulationen reproduziert werden müssen → spezifische Version laden

## Kombinierbarkeit  
- Versionskontrolle für KI-generierte Module  
- Simulation mit Zeitreise-Funktion  
- Vergleich alter/neuer Versionen  
- Forschung & Bildung  
- Fehlersuche & Audit  

## Beispiele  
- Änderung von „Mechanismus“ → MAJOR  
- Hinzufügen eines Beispiels → MINOR  
- Rechtschreibung korrigiert → PATCH  
- Modul widerspricht neuer Erkenntnis → neue MAJOR-Version  

## Visualisierung (textuell)  
Modul v1.0 → Änderung → Validator → v1.1 → Archivierung von v1.0  

## Vorteile  
- klare Nachvollziehbarkeit  
- hohe wissenschaftliche Integrität  
- KI kann korrekt mit Versionen arbeiten  
- ermöglicht reproduzierbare technische Ergebnisse  

## Nachteile  
- erhöhter Pflegeaufwand  
- viele Versionen bei großen Projekten  
- Konflikte möglich, wenn Module stark verzweigen  

## Quellen  
- Semantic Versioning  
- Software-Engineering für Wissensmodelle  
- Datenhistorisierung in Graphdatenbanken
