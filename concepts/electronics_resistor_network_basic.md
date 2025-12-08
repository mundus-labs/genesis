# Modul: Grundlegende Widerstandsnetzwerke (Resistor Networks)  
ID: electronics_resistor_network_basic  
Kategorie: Elektronik / Netzwerke  
Version: 1.0

## Funktion  
Analyse und Berechnung von Widerstandsnetzwerken in Serie, Parallel oder gemischten Strukturen.  
Grundlage für Spannungsteiler, Sensoranpassungen, Leistungspfadkontrolle und Strombegrenzung.

## Prinzip  
Widerstände teilen Spannung, begrenzen Strom und formen elektrische Signale.  
Netzwerke entstehen durch Kombination von Widerständen in Serie, Parallel oder komplexen Topologien.

## Inputs  
- Widerstandswerte  
- Schaltungsstruktur (Serie/Parallel/Mischform)  
- Versorgungsspannung  
- Last (optional)

## Outputs  
- Gesamtwiderstand  
- Stromverteilung  
- Spannungen an einzelnen Knoten  
- Verlustleistung pro Widerstand  

## Grundkonfigurationen  

### 1. Serienschaltung  
R_ges = R₁ + R₂ + ...  
Strom ist überall gleich.

### 2. Parallelschaltung  
1/R_ges = 1/R₁ + 1/R₂ + ...  
Spannung ist überall gleich.

### 3. Spannungsteiler  
U_out = U_in × (R₂ / (R₁ + R₂))  

### 4. Stromteiler  
I_x = I_total × (R_parallel / R_x)

### 5. Leistung pro Widerstand  
P = I²R oder P = U²/R  

## Abhängigkeiten  
- electricity_basic  
- elec_resistor_basic  
- heat_transfer_basic (Verlustwärme)  

## Mechanismus  
1. Widerstände werden zu einem Netzwerk verbunden  
2. Kirchhoff’s Regeln bestimmen Strom- und Spannungsverteilung  
3. Totaler Widerstand berechnet  
4. Verlustleistung geprüft  
5. Netzwerk kann als Teil größerer Elektronik fungieren  

## Kombinierbarkeit  
- Sensorbrücken (z. B. Wheatstone)  
- ADC-Vorbereitung  
- Pegelanpassung  
- Filter (RC-Netzwerke als nächster Schritt)  
- LED-Treiber  
- Leistungsteilernetze  
- Messschaltungen  

## Beispiele  
- Spannungsteiler für Temperatursensor  
- Parallele Leistungswiderstände zur Lastverteilung  
- Serienwiderstände in LEDs  
- Vorwiderstand für Motorsteuerung  
- Wheatstone-Brücke zur Dehnungsmessung  

## Visualisierung (textuell)  
Quelle → R₁/R₂/... → Spannungsteiler/Knoten → Last  

## Vorteile  
- einfache Berechnung  
- universell einsetzbar  
- hohe Zuverlässigkeit  
- Grundbaustein fast jeder Schaltung  

## Nachteile  
- energieineffizient bei hohen Lasten  
- Temperaturabhängigkeit der Widerstände  
- nicht für präzise Regelung geeignet ohne Verstärker  

## Quellen  
- Elektrische Netzwerke / Grundlagen  
- Ohm’sches Gesetz  
- Kirchhoff’sche Knotensatz & Maschensatz
