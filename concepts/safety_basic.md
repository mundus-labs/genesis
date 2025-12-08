# Modul: Grundlegende technische Sicherheit (Safety Fundamentals)  
ID: safety_basic  
Kategorie: Systemtechnik / Sicherheit & Risikomanagement  
Version: 1.0

## Funktion  
Definiert grundlegende Sicherheitsprinzipien, Risikoanalysen und Schutzmechanismen, die bei der Konstruktion technischer Systeme angewendet werden müssen.  
Stellt sicher, dass die Sandbox nur sichere, zuverlässige und verantwortbare Technologien erzeugt.

## Prinzip  
Sicherheit entsteht durch systematische Risikoerkennung, Fehleranalyse, Schutzmechanismen und fail-safe-Design.  
Technische Systeme müssen so gestaltet sein, dass Fehler beherrscht, Schäden vermieden und Nutzer geschützt werden.

## Inputs  
- Systementwürfe  
- Materialdaten  
- Belastungsgrenzen  
- Umgebungseinflüsse  
- Failure Modes  
- HRM-Ethikbewertung  

## Outputs  
- Sicherheitsbewertungen  
- Risikoanalysen  
- empfohlene Schutzmechanismen  
- sicherheitsoptimierte Designs  
- Warnungen bei kritischen Konflikten  

## Sicherheitsdimensionen  

### 1. Funktionale Sicherheit  
- korrektes Verhalten unter Normalbedingungen  
- Überwachung und Diagnose  
- Rückfallebenen

### 2. Strukturelle Sicherheit  
- Materialversagen  
- Überlast  
- Bruchmechanik  
- thermische Stabilität  

### 3. Elektrische Sicherheit  
- Überstromschutz  
- Überspannungsschutz  
- Isolationsanforderungen  
- EMV-Verträglichkeit  

### 4. Mechanische Sicherheit  
- Schutz vor Quetsch-, Scher- und Stoßverletzungen  
- Sicherheitsabstände  
- Abschirmungen

### 5. Software-/Steuersicherheit  
- Watchdog  
- Safe-States  
- Fehlertoleranz  
- redundante Sensorik

### 6. Prozess- & Umgebungssicherheit  
- Temperaturbereiche  
- Feuchtigkeit  
- Vibration  
- chemische oder explosive Atmosphären  

## Methoden der Risikoanalyse  

### FMEA (Failure Mode and Effects Analysis)  
- mögliche Fehler  
- deren Auswirkungen  
- Risikopriorität (RPZ)

### HAZOP  
- systematische Gefahrensuche

### Fault Tree Analysis (FTA)  
- Ursache-Wirkung-Diagramme

### ISO-konforme Sicherheitsklassen  
- SIL (Safety Integrity Level)  
- PL (Performance Level)

## Abhängigkeiten  
- module_format_basic  
- simulation_basic  
- system_design_basic  
- materials_basic  
- control_systems_basic  
- hrm_basic  

## Mechanismus  
1. System wird analysiert  
2. Gefährdungen werden identifiziert  
3. Risiko bewertet (Schweregrad × Wahrscheinlichkeit × Erkennbarkeit)  
4. Gegenmaßnahmen definiert  
5. Simulation bewertet Wirksamkeit  
6. HRM gibt Sicherheits-Score  
7. Sandbox darf nur Systeme ≥ Mindestscore generieren  

## Kombinierbarkeit  
- Robotersysteme  
- elektrische Anlagen  
- mechanische Maschinen  
- embedded Steuerungen  
- Energieanlagen  
- Fahrzeugtechnik  
- Medizintechnik  

## Beispiele  
- Überstromsicherung in Motorantrieben  
- Endschalter zur Kollisionsvermeidung  
- thermische Abschaltung bei Überhitzung  
- doppelte Sensorik für kritische Messungen  

## Visualisierung (textuell)  
Gefahr → Analyse → Gegenmaßnahme → Bewertung → Freigabe → Systemdesign  

## Vorteile  
- verhindert gefährliche Designs  
- fördert verantwortliche Technikentwicklung  
- erhöht Zuverlässigkeit & Lebensdauer  
- Grundlage für regulatorische Konformität  

## Nachteile  
- kann Kreativität einschränken  
- umfangreiche Daten notwendig  
- komplexe Bewertung bei großen Systemen  

## Quellen  
- ISO 12100 – Maschinensicherheit  
- IEC 61508 – Funktionale Sicherheit  
- FMEA / HAZOP Methoden  
- Sicherheitsrichtlinien für Elektrotechnik
