# Modul: Grundlegende Sensorik (Sensors)  
ID: electronics_sensor_basic  
Kategorie: Elektronik / Mess- & Wahrnehmungssysteme  
Version: 1.0

## Funktion  
Erfassung physikalischer Größen und Umwandlung in elektrische Signale.  
Sensoren sind die „Sinne“ technischer Systeme: Temperatur, Druck, Licht, Magnetfeld, Bewegung, Position, Kraft, Gas, Feuchtigkeit u.v.m.

## Prinzip  
Ein physikalischer Einfluss verändert einen elektrischen Parameter:  
- Widerstand  
- Spannung  
- Strom  
- Kapazität  
- Induktivität  
- Frequenz  
- Lichtemission  
- elektromagnetische Kopplung

Der Sensor wandelt diese Änderung in ein nutzbares elektrisches Ausgangssignal um.

## Inputs  
- physikalische Größe  
- Versorgungsspannung  
- Messstrom  
- Referenzsignal (optional)

## Outputs  
- analoges Signal  
- digitales Signal  
- Frequenz  
- Widerstandsänderung  
- Kapazitätsänderung  
- Spannung proportional zur Messgröße  

## Sensorarten  

### 1. Widerstandssensoren  
- Thermistor (NTC/PTC)  
- Dehnungsmessstreifen (DMS)  
- LDR (Lichtabhängiger Widerstand)

### 2. Kapazitive Sensoren  
- Touch  
- Feuchtigkeit  
- Füllstand

### 3. Induktive / Magnetische  
- Hall-Sensor  
- Induktive Näherungsschalter  
- Magnetometer

### 4. Optische Sensoren  
- Photodiode  
- Fototransistor  
- Kamerasensor

### 5. Mechanische  
- Drucksensor  
- Kraftsensor  
- Vibrationssensor (Piezo)

### 6. Digitale Integrierte Sensoren  
- IMU (Gyro + Beschleunigung)  
- Temperatur-ICs  
- Magnetfeldsensoren  
- Luftqualitätssensoren

## Abhängigkeiten  
- electronics_opamp_basic  
- electronics_diode_basic  
- electricity_basic  
- electronics_resistor_network_basic  

## Mechanismus  
1. Physikalische Größe verändert elektrischen Parameter  
2. Elektronik verstärkt/normalisiert Signal (Op-Amp)  
3. Analoges oder digitales Signal wird ausgegeben  
4. Daten können in Steuerungssysteme einfließen  

## Kombinierbarkeit  
- Robotics & Automatisierung  
- Motorsteuerung  
- Messgeräte  
- Smart Devices  
- IoT  
- Kontroll- & Sicherheitssysteme  
- Medizintechnik  

## Beispiele  
- Temperaturmessung mit NTC  
- Lichtmessung mit Photodiode  
- Beschleunigung mit IMU  
- Abstandssensor (Ultraschall, ToF)  
- Drucksensor in Hydrauliksystemen  

## Visualisierung (textuell)  
Physikalische Größe → Sensor → elektrisches Signal → Verstärkung → Auswertung  

## Vorteile  
- hohe Vielfalt  
- elektrische Integration einfach  
- modular kombinierbar  
- ermöglicht echte Regelkreise  

## Nachteile  
- Kalibration notwendig  
- Temperaturdrift  
- Rauschen / Störungen  
- unterschiedliche Signalpegel  

## Quellen  
- Sensorik Grundlagen  
- Messtechnik für Ingenieure  
- Datenblätter gängiger Sensoren (TI, Bosch, Honeywell)
