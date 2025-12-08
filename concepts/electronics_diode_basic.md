# Modul: Grundlegende Dioden (Diodes)  
ID: electronics_diode_basic  
Kategorie: Elektronik / Halbleiter  
Version: 1.0

## Funktion  
Elektrischen Strom in eine Richtung leiten und in der Gegenrichtung sperren.  
Grundlage für Gleichrichter, Schutzschaltungen, LEDs, Solarzellen und Spannungsreferenzen.

## Prinzip  
Eine Diode besteht aus einem p-n-Übergang.  
Strom fließt nur, wenn die Diode in Durchlassrichtung betrieben wird (Forward Bias).  
Bei Rückwärtsbetrieb sperrt sie bis zur Durchbruchspannung.

## Inputs  
- angelegte Spannung  
- Strom  
- Temperatur  
- Diodentyp (Si, Schottky, Zener, LED)  

## Outputs  
- Durchlassspannung  
- Sperrstrom  
- begrenzter Stromfluss  
- Licht (bei LEDs)  

## Grundgleichungen  

### Shockley-Diodengleichung  
I = I₀ (e^(U/(n·V_T)) – 1)  

### Durchlassspannung  
- Silizium: ~0.7 V  
- Schottky: 0.1–0.3 V  
- LED: 1.6–3.5 V (je nach Farbe)

### Zener-Durchbruch  
U_Zener = definierte Referenzspannung

## Diodentypen  

### 1. Standard-Siliziumdiode  
Robust, universell.

### 2. Schottky-Diode  
Niedrige Durchlassspannung, schnell.

### 3. Zener-Diode  
Stabile Referenzspannung, Spannungsreglung.

### 4. LED (Light Emitting Diode)  
Lichtabstrahlung, Wellenlänge abhängig vom Material.

### 5. Photodiode  
Licht → Strom (Sensor).

### 6. Solarzelle  
Licht → elektrische Energie.

## Abhängigkeiten  
- electricity_basic  
- electronics_resistor_network_basic  
- electronics_capacitor_basic  
- heat_transfer_basic  

## Mechanismus  
1. Forward Bias → Diode leitet Strom  
2. Reverse Bias → Diode sperrt  
3. Schnellschaltende Typen reagieren in Nanosekunden  
4. LEDs: Elektronen-Loch-Rekombination erzeugt Photonen  
5. Zener: definierter Durchbruch für Referenzspannungen  

## Kombinierbarkeit  
- Gleichrichter (Einweg, Brücke)  
- Verpolschutz  
- Freilaufdioden bei Motoren/Relais  
- Spannungsregler (Zener)  
- Logikschaltungen (Diode-OR)  
- HF-Mischer / Demodulator  
- Lichtquellen & Sensoren  

## Beispiele  
- Brückengleichrichter im Netzteil  
- LED-Anzeige  
- Freilaufdiode bei Induktivitäten  
- Photodiode für Lichtsensor  
- Zener-Diode als Spannungsreferenz  

## Visualisierung (textuell)  
→|— Strom fließt in Pfeilrichtung  
|←|— sperrt in Gegenrichtung  

## Vorteile  
- einfach und zuverlässig  
- extrem vielseitig  
- viele Spezialtypen verfügbar  

## Nachteile  
- Spannungsabfall erzeugt Wärme  
- empfindlich bei hoher Stromspitze  
- Zenerrauschen bei sehr niedrigen Strömen  

## Quellen  
- Halbleiterphysik: p-n-Übergang  
- Elektronik-Grundlagen  
- Datenblätter zu Diodentypen
