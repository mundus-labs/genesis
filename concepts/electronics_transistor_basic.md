# Modul: Grundlegende Transistoren (Transistors)  
ID: electronics_transistor_basic  
Kategorie: Elektronik / Halbleiter  
Version: 1.0

## Funktion  
Verstärkung, Schalten und Steuern elektrischer Signale.  
Transistoren bilden die Basis moderner Elektronik: von Mikrocontrollern bis zu Motorsteuerungen.

## Prinzip  
Ein kleines Eingangssignal steuert einen großen Stromfluss im Ausgangspfad.  
Transistoren arbeiten als elektrisches Ventil:  
- Eingang bestimmt Leitfähigkeit  
- Ausgangsstrom folgt dem Eingangssignal

## Haupttypen  
### 1. Bipolartransistor (BJT) – NPN / PNP  
Stromgesteuert:  
I_C ≈ β × I_B  
(β = Stromverstärkung)

### 2. Feldeffekttransistor (FET / MOSFET)  
Spannungsgesteuert:  
Gate-Spannung kontrolliert Leitfähigkeit des Kanals.

### 3. IGBT  
Kombination aus MOSFET-Steuerung + BJT-Ausgang  
→ ideal für hohe Spannungen/Ströme.

## Inputs  
- Steuerspannung oder Steuerstrom  
- Versorgungsspannung  
- Last  
- Temperatur  

## Outputs  
- Stromverstärkung  
- geschaltete Last  
- verstärktes Ausgangssignal  
- Leistungsverstärkung  

## Grundgleichungen  

### BJT  
I_C = β × I_B  
I_E = I_B + I_C  

### MOSFET (vereinfachtes Modell)  
I_D ∝ (V_GS – V_th)² in Sättigung  
V_th = Threshold-Spannung  

### Schaltverluste  
P = V × I × t_switch  

## Betriebsbereiche  

### BJT  
- Sperrbereich  
- aktiver Bereich (Verstärkung)  
- Sättigung (Schalter EIN)

### MOSFET  
- Cutoff  
- Linear (Widerstandsmodus)  
- Sättigung (Schalter EIN)

## Abhängigkeiten  
- electricity_basic  
- electronics_resistor_network_basic  
- electronics_diode_basic  
- heat_transfer_basic (Verlustleistung)  
- dynamics_basic (Switching-Verhalten)

## Mechanismus  
1. Eingangssignal steuert Transistor-Gate/Basis  
2. Ausgangspfad wird leitend oder sperrt  
3. Verstärkung oder Schalten erfolgt  
4. Schnelles Ein-/Ausschalten ermöglicht digitale Logik  
5. Powertransistoren steuern Motoren, LEDs, Aktuatoren  

## Kombinierbarkeit  
- Verstärker  
- Logikgatter  
- Schaltregler  
- Motorcontroller  
- Treiber für LEDs & Relais  
- Sensorvorverstärker  
- RF-Verstärker  
- CMOS-Logik (Milliarden Transistoren pro Chip)

## Beispiele  
- NPN-Transistor als Schalter für LED  
- MOSFET steuert Motor  
- BJT-Verstärker  
- CMOS-NAND-Gate  
- IGBT in einem Frequenzumrichter  

## Visualisierung (textuell)  
Signal (klein) → Transistor → steuert großen Strom → Last  

## Vorteile  
- extrem vielseitig  
- schnelle Schaltzeiten  
- hohe Verstärkung  
- winzige Größen möglich (Nanometerbereich)  

## Nachteile  
- empfindlich gegenüber Hitze & Überspannung  
- Gate-ESD-Empfindlichkeit bei MOSFETs  
- benötigt korrekte Beschaltung  

## Quellen  
- Halbleitertechnik: Transistoren  
- CMOS Digital Logic Design  
- Leistungselektronik Grundlagen
