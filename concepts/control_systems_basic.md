# Modul: Grundlegende Regelungstechnik (Control Systems)  
ID: control_systems_basic  
Kategorie: Systemtechnik / Steuerung & Regelung  
Version: 1.0

## Funktion  
Stabilisierung, Präzisionssteuerung und automatische Anpassung eines Systems durch Feedback.  
Regelungen sorgen dafür, dass Systeme korrekt, sicher und effizient arbeiten.

## Prinzip  
Ein Regelsystem vergleicht den **Sollwert** mit dem **Istwert**, berechnet die Abweichung (Fehler) und passt das Eingangssignal an, um den Fehler zu minimieren.

→ ohne Regelungen wären Motoren, Drohnen, Heizungen, Roboter und Energiesysteme nicht kontrollierbar.

## Inputs  
- Sollwert  
- Istwert (Sensor)  
- Modelldaten  
- Störgrößen  

## Outputs  
- Steuersignal  
- stabilisiertes Systemverhalten  
- Fehlerkorrektur  

## Hauptkomponenten  

### 1. Regler  
- P-Regler (Proportional)  
- PI-Regler  
- PD-Regler  
- PID-Regler (Industrie-Standard)  
- State-Space-Regler  
- MPC (Model Predictive Control)

### 2. Regelstrecke  
Das physische System: Motor, Temperatur, Position, Geschwindigkeit, Druck, etc.

### 3. Sensor  
Ermittelt den Istwert.

### 4. Aktuator  
Setzt die Stellgröße um (Motor, Ventil, Heizer …).

## Grundgleichungen  

### P-Regler  
u = Kp × e  

### PI-Regler  
u = Kp × e + Ki ∫ e dt  

### PID-Regler  
u = Kp × e + Ki ∫ e dt + Kd × de/dt  

### Übertragungsfunktion  
G(s) = Ausgang(s) / Eingang(s)

### Stabilitätskriterien  
Nyquist, Bode, Pol-Nullstellen

## Abhängigkeiten  
- embedded_microcontroller_basic  
- electronics_sensor_basic  
- motor_electric_basic  
- dynamics_basic  
- power_supply_basic  

## Mechanismus  
1. Sensor misst den Istwert  
2. Regler berechnet die Abweichung  
3. Stellgröße wird berechnet  
4. Aktuator verändert das System  
5. Neuer Istwert wird gemessen → Feedback Loop  

## Kombinierbarkeit  
- Motorsteuerung (Drehzahl, Position, Drehmoment)  
- Robotik (Arm-Regelung, Stabilisierung)  
- Drohnen (Flight Controller)  
- Temperaturregelung (PID)  
- Fahrzeugtechnik (ABS, ESP)  
- Industrieanlagen  
- Hydraulik / Pneumatik  

## Beispiele  
- BLDC-Motor mit PID-Drehzahlregelung  
- Temperaturkontrolle in Öfen  
- Druckregelung in Pneumatik  
- Selbstbalancierender Roboter  
- Drohnen-Stabilisierung (Roll, Pitch, Yaw)

## Visualisierung (textuell)  
Sollwert → Regler → Aktuator → System → Sensor → zurück zum Regler  

## Vorteile  
- präzise Kontrolle  
- stabilisiert instabile Systeme  
- reduziert Störungen  
- ermöglicht autonome Systeme  

## Nachteile  
- benötigt genaue Parameter  
- schlecht eingestellte Regler führen zu Instabilität  
- manche Systeme nichtlineare oder zeitverzögert  

## Quellen  
- Grundlagen der Regelungstechnik  
- PID-Design und Tuning  
- Control Systems Engineering (Ogata)
