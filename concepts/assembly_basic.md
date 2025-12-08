# Modul: Grundlegende Montage & Baugruppen (Assembly Fundamentals)  
ID: assembly_basic  
Kategorie: Systemtechnik / Struktur & Baugruppen  
Version: 1.0

## Funktion  
Definiert die grundlegenden Prinzipien, mit denen integrierte Systemmodule zu physischen Baugruppen, Unterbaugruppen und kompletten Geräten strukturiert und zusammengebaut werden.  
Ermöglicht der Sandbox, aus Systemdesigns konkrete, real montierbare Strukturen zu erzeugen.

## Prinzip  
Montage bedeutet, Module physisch, energetisch und funktional so zu verbinden, dass ein vollständiges, stabiles und einsatzfähiges System entsteht.  
Die Assembly-Schicht überführt logische Integrationen in reale Bauteile, Befestigungen, Geometrien und Montageprozesse.

## Inputs  
- integrierte Systemarchitektur  
- Modul-Schnittstellen  
- mechanische & elektrische Anforderungen  
- Fertigungsdaten  
- Stückzahlen  
- Sicherheitsregeln  

## Outputs  
- Baugruppenstruktur  
- physische Verbindungsdefinitionen  
- Stückliste (BOM – Bill of Materials)  
- Montageanweisungen  
- Positionierungs- & Befestigungspunkte  
- Assembly-Constraints  

## Montagestruktur  

### 1. Komponentenebene  
Einzelteile (Sensor, Schraube, Motor, PCB).

### 2. Baugruppen  
Mehrere Komponenten bilden ein Funktionsmodul.

### 3. Subsysteme  
Baugruppen werden zu funktionalen Einheiten kombiniert.

### 4. Gesamtsystem  
Alle Subsysteme ergeben das vollständige Gerät.

## Assembly-Prinzipien  

### 1. Mechanische Befestigung  
- Schrauben  
- Nuten  
- Passungen  
- Klemmverbindungen  
- Pressverbindungen  
- Schweißpunkte

### 2. Elektrische Verbindung  
- Stecker  
- Lötstellen  
- Leiterbahnen (PCB)  
- Kabelbäume  
- Busleitungen  

### 3. Energietransfer  
- Drehmomentpfade  
- Wärmepfade  
- Fluidleitungen  

### 4. Montagefreundlichkeit (DFMA – Design for Assembly)  
- wenige Teile  
- intuitive Ausrichtung  
- robuste Verbindungen  
- minimale Toleranzkritik  

### 5. Modultauschbarkeit  
Austauschbare Module erleichtern Reparatur & Upgrades.

## Abhängigkeiten  
- integration_logic_basic  
- interface_definition_basic  
- manufacturing_basic  
- system_design_basic  
- materials_basic  
- safety_basic  

## Mechanismus  
1. Sandbox erhält vollständiges Systemdesign  
2. Assembly-Engine erkennt Baugruppen  
3. Physische Schnittstellen werden konkretisiert  
4. Kompatible Befestigungen & Leitungen werden zugeordnet  
5. Toleranzen & Materialstärken werden geprüft  
6. Stückliste wird automatisch generiert  
7. Montageablauf & Reihenfolge festgelegt  
8. System wird validiert (Simulation optional)

## Kombinierbarkeit  
- Robotersysteme  
- mechanische Maschinen  
- Elektronikgeräte  
- mechatronische Baugruppen  
- Gehäuse- & Rahmenstrukturen  
- modulare Systeme  

## Beispiele  
- Drohnenarm: Motor + Halterung + Propeller + Verkabelung + Sensor  
- PCB-Baugruppe: Mikrocontroller + Sensoren + Stecker + Spannungsregler  
- Pumpensystem: Motor + Pumpe + Kupplung + Dichtungen + Rohrleitungen  

## Visualisierung (textuell)  
Komponenten → Baugruppen → Subsysteme → Gerät → Montageplan  

## Vorteile  
- erzeugt reale baubare Strukturen  
- klare Zuordnung mechanischer & elektrischer Verbindungen  
- automatische BOM-Erstellung  
- kompatibel mit Fertigung & Sicherheit  
- reduziert Montagezeit & Fehler  

## Nachteile  
- komplexe geometrische Aspekte  
- viele Domänen müssen berücksichtigt werden  
- erfordert detaillierte Material- & Fertigungsdaten  

## Quellen  
- Design for Manufacturing & Assembly (DFMA)  
- Mechanical Assembly Principles  
- PCB Assembly Guidelines  
- Modular Systems Engineering
