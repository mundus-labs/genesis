# Modul: Grundlegendes Modulformat (Module Format Specification)  
ID: module_format_basic  
Kategorie: Meta / Standards & Struktur  
Version: 1.0

## Funktion  
Definiert die formale Struktur (MMF – MUNDUS Module Format) für alle Wissensmodule.  
Stellt sicher, dass jedes Modul maschinenlesbar, kombinierbar und in den Wissensgraph integrierbar ist.

## Prinzip  
Alle technischen Informationen werden in eine einheitliche, klar strukturierte Form gebracht.  
Dadurch können KI, Wissensgraph, Simulation und Sandbox automatisch darauf zugreifen und Module sinnvoll verbinden.

## Inputs  
- Rohwissen (Patente, Dokumente, technische Beschreibungen)  
- formale Moduldefinition  
- Klassifizierung  
- menschliche Validierung  

## Outputs  
- standardisierte Module  
- kompatible Wissenseinträge  
- eindeutige IDs  
- Graph-Knoten  
- konsistente technische Daten  

## Struktur eines MUNDUS-Moduls (MMF)  
Jedes Modul MUSS folgende Abschnitte enthalten:

### 1. Kopfbereich  
- **Modulname**  
- **ID** (einzigartig, lowercase, domain_prefix)  
- **Kategorie**  
- **Version**  

### 2. Funktion  
Kurzbeschreibung des Zwecks des Moduls.

### 3. Prinzip  
Grundlegender Mechanismus oder physikalische/e Techniken.

### 4. Inputs  
Alle Größen, Parameter, Signale oder Energieformen, die das Modul benötigt.

### 5. Outputs  
Erzeugte Aktionen, Signale, Bewegungen, Zustände oder Energieformen.

### 6. Abhängigkeiten  
Andere Module, die für Verständnis oder Funktion notwendig sind.

### 7. Mechanismus  
Detaillierte technische Beschreibung, wie das Modul arbeitet.

### 8. Kombinierbarkeit  
Liste möglicher Integration in Systeme oder Kombinationen mit anderen Modulen.

### 9. Beispiele  
Konkrete Anwendungen, in denen das Modul typischerweise vorkommt.

### 10. Visualisierung (textuell)  
Kurze abstrakte Darstellung des Funktionsflusses.

### 11. Vorteile  
Stärken des Moduls.

### 12. Nachteile  
Grenzen, Risiken oder typische Fehler.

### 13. Quellen  
Wissenschaftliche, technische oder historische Referenzen.

## Regeln für Modul-IDs  
- format: `domainname_subdomainname_basic`  
- nur Kleinbuchstaben  
- keine Leerzeichen  
- eindeutig im gesamten Repo

Beispiele:  
- `mech_gear_basic`  
- `electronics_diode_basic`  
- `energy_conversion_basic`  

## Dateiformat  
- Markdown `.md`  
- UTF-8  
- Keine externen Anhänge  
- Text-only (Bilder später durch Tools generierbar)

## Abhängigkeiten  
- knowledge_graph_basic  
- ai_assistant_basic  
- hrm_basic  

## Mechanismus  
1. Mensch oder KI erstellt Roh-Entwurf  
2. Rohformat wird in MMF übertragen  
3. Validierung der Felder  
4. Modul wird in Graph registriert  
5. KI-Sandbox kann es kombinieren  
6. Änderungen werden versioniert  

## Kombinierbarkeit  
- universell für alle Domains  
- technische, physikalische, logische Module  
- Meta-Module  
- Simulation & KI  

## Beispiele  
- Modul beschreibt einen Kondensator → Simulation nutzt Werte  
- Modul beschreibt einen Motor → Regler nutzt Mechanismus  
- Modul beschreibt ein Protokoll → MCU integriert Buslogik  
- Modul beschreibt ein Patentprinzip → KI generiert neue Anwendungen  

## Visualisierung (textuell)  
Rohwissen → MMF → Graph-Knoten → KI/Sandbox → Systemdesign  

## Vorteile  
- vollständige Standardisierung  
- hohe KI-Kompatibilität  
- automatische Kombinierbarkeit  
- eindeutige Struktur  
- klare technische Lesbarkeit  

## Nachteile  
- strikte Form kann Kreativität begrenzen  
- benötigt konsequente Pflege  
- Versionierung aufwendig bei großen Änderungen  

## Quellen  
- Ontologie-Design  
- Technische Dokumentationsstandards  
- Daten- und Wissensgraph-Formate  
- Modular Engineering Frameworks
