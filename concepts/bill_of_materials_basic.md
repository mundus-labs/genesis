# Modul: Grundlegende Stückliste (Bill of Materials – BOM Fundamentals)  
ID: bill_of_materials_basic  
Kategorie: Produktion / Komponenten & Ressourcen  
Version: 1.0

## Funktion  
Erstellt strukturierte, vollständige und hierarchische Stücklisten für Systeme, die aus MUNDUS-Modulen konstruiert wurden.  
BOM-Module ermöglichen Kostenkalkulation, Materialplanung, Variantenmanagement und Fertigungsintegration.

## Prinzip  
Eine Stückliste beschreibt alle Bauteile, Materialien, Baugruppen und Subsysteme, die für den Bau eines technischen Systems notwendig sind.  
Die BOM folgt der Systemhierarchie: Komponenten → Baugruppen → Subsysteme → Gesamtsystem.

## Inputs  
- Systemarchitektur  
- Moduldefinitionsdaten (MMF)  
- Assembly-Struktur  
- Materialinformationen  
- Fertigungsdaten  
- Variantenparameter  

## Outputs  
- vollständige Stückliste  
- Baugruppenstruktur  
- Materialmengen  
- Kostenabschätzung  
- Varianten-BOM  
- Exportformate (textuell, hierarchisch)  

## BOM-Typen  

### 1. Strukturierte BOM (hierarchisch)  
Abbildung der Systemstruktur (Parent/Child).  
Ideal für Montage.

### 2. Mengen-BOM (flattened BOM)  
Alle Teile aufsummiert ohne Hierarchie.  
Ideal für Einkauf.

### 3. Varianten-BOM  
Unterschiedliche Konfigurationen eines Systems (z. B. Standard vs. Premium).

### 4. Fertigungs-BOM (mBOM)  
Bauteile nach Fertigungsschritten gruppiert.

### 5. Engineering-BOM (eBOM)  
Direkt aus dem Design generiert.

## Hauptinhalte einer BOM  

- Bauteilname  
- Bauteil-ID  
- Menge  
- Kategorie  
- Material  
- Preis (optional)  
- Lieferant (optional)  
- Gewicht  
- Baugruppenzugehörigkeit  
- Abmessungen (optional)  
- Fertigungsinformationen  

## Abhängigkeiten  
- assembly_basic  
- system_design_basic  
- manufacturing_basic  
- materials_basic  
- integration_logic_basic  

## Mechanismus  
1. Sandbox analysiert die Systemarchitektur  
2. Assembly liefert Baugruppenstruktur  
3. BOM-Engine extrahiert alle Module und Komponenten  
4. Mengen und Hierarchie werden automatisch berechnet  
5. Material- & Fertigungsdaten werden hinzugefügt  
6. Varianten werden aus Parametern generiert  
7. BOM wird validiert (keine fehlenden Teile, keine Duplikate)  
8. Ausgabe an Fertigung & Kostenplanung  

## Kombinierbarkeit  
- Serienfertigung  
- Variantenkonfiguration  
- Einkauf/Materialwirtschaft  
- Produktionsplanung  
- Montageoptimierung  
- Ökobilanzierung (CO₂/Materialflussanalyse)  

## Beispiele  
- Drohne: Motoren, Propeller, IMU, Rahmen, Schrauben, ESC, PCB, Akku  
- Steuergerät: PCB, MCU, Sensoren, Stecker, Gehäuse  
- Pumpensystem: Motor, Pumpenkopf, Dichtungen, Leitungen, Halterungen  

## Visualisierung (textuell)  
System → Baugruppen → Teileliste → Mengen & Kosten  

## Vorteile  
- automatische, fehlerfreie Stücklisten  
- klare Struktur  
- kompatibel mit Fertigung & Einkauf  
- Varianten werden automatisch erzeugt  
- hohe Skalierbarkeit  

## Nachteile  
- benötigt konsistente Moduldefinitionen  
- Preis- und Lieferantendaten variieren  
- komplexe Varianten erzeugen große BOMs  

## Quellen  
- Produktionssysteme & PPS  
- Engineering Bill of Materials Standards  
- Manufacturing Resource Planning (MRP)
