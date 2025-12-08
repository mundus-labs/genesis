# Modul: Grundlegende Kommunikationsprotokolle (Communication Protocols)  
ID: communication_protocols_basic  
Kategorie: Elektronik / Digitale Kommunikation  
Version: 1.0

## Funktion  
Übertragung von Daten zwischen Mikrocontrollern, Sensoren, Aktuatoren und digitalen Systemen.  
Protokolle definieren elektrische Signale, Taktung, Datenrahmen und Fehlererkennung.

## Prinzip  
Ein Kommunikationsprotokoll legt fest, wie Informationen kodiert, gesendet, empfangen und bestätigt werden.  
Es regelt Datenformat, Übertragungsgeschwindigkeit, Adressierung und Timing.

## Inputs  
- Bits / Datenframes  
- Takt (falls synchron)  
- Protokollkonfiguration  
- Hardware-Signale (GPIO, Pins, Lanes)

## Outputs  
- Datenübertragung  
- empfangene Nachrichten  
- Bus-Kommunikation  
- Fehlercodes  

## Hauptprotokolle  

### 1. UART (seriell, asynchron)  
- 2 Leitungen: TX, RX  
- keine Taktleitung  
- einfach, universell  
- genutzt für Debug, Sensoren, Module

### 2. I2C (Inter-Integrated Circuit)  
- 2 Leitungen: SDA, SCL  
- Master/Slave  
- mehrere Geräte am Bus  
- ideal für Sensoren

### 3. SPI (Serial Peripheral Interface)  
- 4+ Leitungen: MOSI, MISO, SCK, CS  
- sehr schnell  
- Punkt-zu-Punkt oder Bus  
- ideal für Displays, ADCs, Speicher

### 4. CAN-Bus (Controller Area Network)  
- robust, störfest  
- priorisierte Nachrichten  
- Automotive, Industrie

### 5. LIN-Bus  
- günstiger, langsamer als CAN  
- Automotive-Subsysteme

### 6. USB  
- differenzielles Hochgeschwindigkeitssignal  
- Host/Client  
- viele Klassen (HID, CDC, Mass Storage)

### 7. Ethernet  
- lange Strecken  
- hohe Bandbreite  
- TCP/IP, UDP  
- Industrie 4.0, Netzwerktechnik  

## Wichtige Begriffe  
- Baudrate (Geschwindigkeit)  
- Parität  
- Stopbits  
- Bus-Arbitration  
- Pull-Up-Widerstände (I2C)  
- Chip-Select (SPI)  
- CRC-Checksummen  

## Abhängigkeiten  
- embedded_microcontroller_basic  
- electronics_sensor_basic  
- motor_electric_basic  
- power_supply_basic  

## Mechanismus  
1. Daten werden in Frames codiert  
2. Physikalische Schicht überträgt Bits  
3. Empfänger dekodiert Daten  
4. Fehlererkennung (CRC/Parity) prüft Integrität  
5. Busprotokolle verwalten Prioritäten und Adressierung  

## Kombinierbarkeit  
- Sensor-Netzwerke  
- Motorsteuerungen  
- IoT-Geräte  
- Robotik  
- Automatisierung  
- industrielle Bus-Systeme  
- Mensch-Maschine-Schnittstellen  

## Beispiele  
- I2C-Temperatursensor  
- SPI-Display  
- UART-Kommandointerface  
- CAN im Auto  
- Ethernet für CNC- oder PLC-Systeme  
- USB-Mikrocontrollerprogrammierung  

## Visualisierung (textuell)  
Datenbits → Protokoll → physikalische Leitungen → Empfänger → Verarbeitung  

## Vorteile  
- strukturierte, zuverlässige Datenübertragung  
- große Vielfalt an Protokollen für jede Anwendung  
- ermöglicht modulare Systeme  

## Nachteile  
- Timing-sensitiv  
- Störungen/Streckenabhängigkeiten  
- unterschiedliche elektrische Pegel  

## Quellen  
- Embedded Communication Fundamentals  
- I2C/SPI/UART/CAN Spezifikationen  
- Netzwerkgrundlagen (Ethernet/USB)
