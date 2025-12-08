# Modul: Grundlegende Schnittstellendefinition (Interface Definition Fundamentals)  
ID: interface_definition_basic  
Kategorie: Systemtechnik / Modul-Interoperabilität  
Version: 1.0

## Funktion  
Definiert standardisierte Schnittstellentypen, die es MUNDUS-Modulen ermöglichen, eindeutig, sicher und maschinenlesbar miteinander verbunden zu werden.  
Schnittstellen sind die „Andockpunkte“ aller Module und bilden das verbindende Fundament der Sandbox.

## Prinzip  
Jedes Modul besitzt definierte Inputs und Outputs, die entweder Energie, Signale, Kräfte oder Informationen transportieren.  
Schnittstellen stellen sicher, dass nur kompatible Module verbunden werden können.

## Inputs  
- Moduldefinitionen (MMF)  
- physikalische / logische Parameter  
- Systemdesign-Anforderungen  
- Kommunikationsprotokolle  
- mechanische Geometrien  

## Outputs  
- standardisierte Interface-Beschreibungen  
- Kompatibilitätsmatrix  
- Verbindungsspezifikationen  
- Fehlermeldungen bei Inkonsistenzen  

## Hauptschnittstellentypen  

### 1. Elektrische Schnittstellen  
Definiert durch:  
- Spannung  
- Strom  
- Impedanz  
- Polarität  
- Steckverbindertypen  
- Schutzfunktionen  

Beispiele: 5V-DC, 12V-DC, GND, PWM, Analog 0–3.3V, UART, I2C, CAN.

### 2. Mechanische Schnittstellen  
Definiert durch:  
- Geometrie  
- Bohrungen  
- Toleranzen  
- Kraftübertragungsflächen  
- Kupplungstypen  

Beispiele: Welle-D10, Schrauben M3, Zahnradmodul m=1.

### 3. Energetische Schnittstellen  
Definiert durch:  
- Drehmoment  
- Leistung  
- Wärmefluss  
- Druck / Durchfluss  
- Frequenz  

Beispiele: Motorwelle → Getriebe, Heizleistung → Kühlung.

### 4. Informationsschnittstellen  
Definiert durch:  
- Datenformat  
- Protokoll  
- Timing  
- Bandbreite  
- Adressierung  

Beispiele: JSON, SPI-Frames, Sensordatenpakete.

### 5. Logische Schnittstellen  
- Zustandsmodelle  
- Regler-Eingänge  
- Aktuator-Kommandos  
- Fehlermeldungen  

Ermöglichen vollständige autonome Systeme.

## Kompatibilitätskriterien  

### 1. physikalisch korrekt  
Spannungen, Kräfte, Drehmomente, Temperaturen müssen übereinstimmen.

### 2. protokollkompatibel  
Gleiche Kommunikationssprache.

### 3. geometrisch passend  
Mechanische Verbindung möglich.

### 4. sicherheitskonform  
Keine gefährlichen Kombinationen.

### 5. funktional sinnvoll  
Signalfluss unterstützt Systemziel.

## Abhängigkeiten  
- module_format_basic  
- system_design_basic  
- communication_protocols_basic  
- electronics_sensor_basic  
- safety_basic  
- knowledge_graph_basic  

## Mechanismus  
1. Modul definiert Schnittstellen im MMF  
2. Schnittstellen-Typen werden klassifiziert  
3. KI überprüft Kompatibilität  
4. Sandbox verknüpft Module automatisch  
5. Inkompatible Schnittstellen → Fehlermeldung  
6. Systemdesign wird angepasst oder optimiert  
7. Schnittstellen fließen in Simulation ein  

## Kombinierbarkeit  
- Modulverkettung in der Sandbox  
- automatische Systemarchitektur  
- generative Designs  
- Multi-Domain-Integration (Mechanik + Elektronik + Software)  
- Validierung von Energie- und Signalpfaden  

## Beispiele  
- Motor (Drehmoment-Interface) passt zu Getriebe (Drehmomentaufnahme)  
- Sensor (I2C) passt zu MCU (I2C-Master)  
- OpAmp-Ausgang → ADC-Eingang  
- Netzteil 5V → Logiksystem 3.3V → inkompatibel (Fehler + Empfehlung)

## Visualisierung (textuell)  
Modul A Output → Interface → Modul B Input → funktionale Verbindung  

## Vorteile  
- eindeutige Regeln  
- automatische KI-Checks  
- universelle Kombinierbarkeit  
- weniger Fehler in Systemdesign  
- konsistente technische Sprache  

## Nachteile  
- strikte Definitionen notwendig  
- Spezialfälle erfordern Erweiterungen  
- komplex bei Multi-Domain-Systemen  

## Quellen  
- Interface Control Documents (ICD)  
- Systems Engineering Standards  
- Electrical/Mechanical Interface Normen  
- Kommunikationsprotokoll-Design
