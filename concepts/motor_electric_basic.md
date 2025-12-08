# Modul: Grundlegende Elektromotoren (Electric Motors)  
ID: motor_electric_basic  
Kategorie: Elektromechanik / Antriebstechnik  
Version: 1.0

## Funktion  
Umwandlung elektrischer Energie in mechanische Drehbewegung.  
Elektromotoren erzeugen kontrollierbare Drehzahl, Drehmoment und dynamisches Bewegungsverhalten.

## Prinzip  
Ein Magnetfeld wirkt auf stromdurchflossene Leiter → Lorentzkraft erzeugt Drehmoment.  
Wechselnde Magnetfelder (kommutiert oder elektronisch gesteuert) erzeugen kontinuierliche Rotation.

## Inputs  
- elektrische Spannung oder Strom  
- Frequenz (bei AC-Motoren)  
- Steuerungssignale (PWM, H-Brücke, ESC)  

## Outputs  
- Drehmoment  
- Drehzahl  
- mechanische Leistung  
- Wärme (Verluste)

## Hauptmotorarten  

### 1. DC-Motor (gebürstet)  
- einfache Ansteuerung  
- Kommutator mechanisch  
- Drehzahl ∝ Spannung

### 2. Brushless DC (BLDC)  
- elektronisch kommutiert  
- hohe Effizienz  
- typische Motoren in Drohnen, Werkzeugen, EVs

### 3. Schrittmotor  
- diskrete Schritte  
- präzise Positionierung  
- benötigt Treiber

### 4. AC-Induktionsmotor  
- robust, hohe Leistung  
- Drehfeld durch AC  
- weit verbreitet in Industrie

### 5. Synchronmotor  
- konstante Drehzahl  
- Permanentmagnet oder elektromagnetischer Rotor

## Grundgleichungen  

### Drehzahl  
ω ≈ U / k_e  (vereinfachtes DC-Modell)

### Drehmoment  
τ = k_t × I

### Mechanische Leistung  
P_mech = τ × ω

### Wirkungsgrad  
η = P_mech / P_elec

## Abhängigkeiten  
- electricity_basic  
- electronics_transistor_basic  
- electronics_diode_basic (Freilaufdioden)  
- electronics_sensor_basic (Hall-Sensoren bei BLDC)  
- dynamics_basic  
- heat_transfer_basic  

## Mechanismus  
1. Strom erzeugt Magnetfeld  
2. Magnetfeld interagiert mit Rotor  
3. Kräfte erzeugen Drehmoment  
4. Elektronik steuert Timing (PWM, ESC, H-Brücke)  
5. Motor bewegt Last → mechanische Arbeit entsteht  

## Kombinierbarkeit  
- Robotikantriebe  
- Pumpen und Lüfter  
- Linearaktuatoren (Gewindespindel + Motor)  
- Fahrzeugantriebe  
- Industriemaschinen  
- CNC & 3D-Drucker (Stepper)  
- Drohnen & UAVs  

## Beispiele  
- 12V-DC-Motor in Modellbau  
- BLDC-Motor in Drohnen  
- Induktionsmotor in Waschmaschinen  
- Schrittmotor in 3D-Druckern  
- Permanentmagnetmotor im Elektroauto  

## Visualisierung (textuell)  
Elektrizität → Magnetfeld → Rotor dreht → mechanische Leistung  

## Vorteile  
- hohe Effizienz  
- präzise steuerbar  
- große Variantenvielfalt  
- skalierbar von Milliwatt bis Megawatt  

## Nachteile  
- Wärmeentwicklung  
- Steuerung teils komplex (BLDC, Stepper)  
- Magnetverlust bei Hitze (PM-Motor)  

## Quellen  
- Elektromotoren: Grundlagen  
- Elektrische Maschinen (Katalogwissen)  
- Leistungselektronik für Motorantriebe
