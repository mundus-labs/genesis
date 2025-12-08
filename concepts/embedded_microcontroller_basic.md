# Modul: Grundlegende Mikrocontroller (Embedded Microcontrollers)  
ID: embedded_microcontroller_basic  
Kategorie: Elektronik / Digitale Systeme  
Version: 1.0

## Funktion  
Ausführen von Programmen zur Steuerung, Regelung, Messung und Kommunikation in eingebetteten Systemen.  
Mikrocontroller verbinden Sensoren, Aktuatoren und Elektronik zu intelligenten Systemen.

## Prinzip  
Ein Mikrocontroller integriert CPU, Speicher, Timer und Peripherie auf einem einzigen Chip.  
Er verarbeitet Eingaben, führt Software aus und generiert Ausgänge in Echtzeit.

## Inputs  
- Versorgungsspannung  
- digitale/analoge Eingänge  
- Sensorwerte  
- Kommunikationssignale  
- Softwareprogramm (Firmware)

## Outputs  
- digitale Signale (GPIO)  
- PWM-Ansteuerungen  
- analoge Ausgänge (DAC)  
- Motorsteuerung  
- Kommunikationsdaten (UART, I2C, SPI, CAN)

## Hauptkomponenten eines Mikrocontrollers  
- CPU (8/16/32 Bit)  
- RAM (flüchtig)  
- Flash (Programm)  
- Timer  
- ADC (Analog-Digital-Wandler)  
- DAC (Digital-Analog-Wandler)  
- PWM-Module  
- Watchdog  
- Interrupt-Controller  
- Peripheriebusse (I2C, SPI, UART, CAN, USB)  

## Wichtige Größen  
- Taktfrequenz  
- Word-Length (8/32 Bit)  
- Stromverbrauch  
- ADC-Auflösung (z. B. 12 Bit)  
- Flashgröße  
- GPIO-Anzahl  

## Beispielarchitekturen  
- AVR (Atmega)  
- ARM Cortex-M (STM32, RP2040, ESP32)  
- RISC-V MCUs  
- PIC-Mikrocontroller  
- ESP32 (mit WiFi/Bluetooth)

## Abhängigkeiten  
- power_supply_basic  
- electronics_sensor_basic  
- electronics_transistor_basic  
- electronics_diode_basic  
- electronics_opamp_basic  
- motor_electric_basic  

## Mechanismus  
1. Firmware wird geflasht  
2. CPU führt Instruktionen aus  
3. Eingänge werden gelesen (ADC, GPIO)  
4. Logik/Regelung wird berechnet  
5. Ausgänge steuern Motoren, LEDs, Ventile, Pumpen usw.  
6. Kommunikation über I2C/SPI/UART/CAN  

## Kombinierbarkeit  
- Robotersteuerung  
- Sensor-Hubs  
- Motorsteuerungen  
- IoT-Geräte  
- industrielle Automatisierung  
- Drohnen  
- Messgeräte und Regler  
- Haushaltsgeräte  

## Beispiele  
- PWM für Motorsteuerung  
- Temperaturmessung über ADC  
- I2C-Kommunikation mit Sensoren  
- UART-Debug  
- Echtzeitsteuerung in Embedded Systems  

## Visualisierung (textuell)  
Sensoren → ADC/GPIO → MCU → Logik → PWM/Steuerung → Aktuatoren  

## Vorteile  
- extrem flexibel  
- energieeffizient  
- große Ökosysteme & Bibliotheken  
- vereint viele Funktionen auf kleiner Fläche  

## Nachteile  
- Echtzeitbeschränkungen  
- benötigt Firmwareentwicklung  
- begrenzte Rechenleistung  
- Timing-sensitiv  

## Quellen  
- Embedded Systems Fundamentals  
- ARM Cortex-M Architektur  
- Datenblätter von STM, Microchip, Espressif
