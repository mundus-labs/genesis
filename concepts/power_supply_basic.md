# Modul: Grundlegende Stromversorgung (Power Supply)  
ID: power_supply_basic  
Kategorie: Elektronik / Energieversorgung  
Version: 1.0

## Funktion  
Bereitstellung stabiler elektrischer Energie für elektronische und mechanische Systeme.  
Netzteile wandeln Eingangsspannungen um, stabilisieren sie und schützen Lasten.

## Prinzip  
Eine Stromversorgung besteht aus:  
1. Energiequelle (Netz, Akku, Solar)  
2. Umwandlung (Transformator, Gleichrichter, DC/DC)  
3. Glättung (Kondensatoren)  
4. Stabilisierung (Linearregler oder Schaltregler)  
5. Schutz (Sicherung, Dioden, Überspannung)

## Inputs  
- AC-Spannung (230 V, 120 V)  
- DC-Spannung (Batterie, Netzteil)  
- Laststrom  
- Ripple / Störungen  

## Outputs  
- geregelte Gleichspannung  
- begrenzter Strom  
- Schutzfunktionen  
- Restwelligkeit (Ripple)  

## Hauptkomponenten  

### 1. Transformator  
Reduziert oder erhöht AC-Spannung.  
Isolation vom Netz.

### 2. Gleichrichter  
- Einweggleichrichter  
- Brückengleichrichter  
→ erzeugt pulsierende DC

### 3. Glättung  
Kondensatoren reduzieren Ripple.

### 4. Lineare Spannungsregler (LDO)  
→ einfache, saubere Ausgangsspannung  
→ ineffizient bei großen Spannungsdifferenzen

### 5. Schaltregler (Switching Regulators)  
- Buck (Step-Down)  
- Boost (Step-Up)  
- Buck-Boost  
→ hohe Effizienz, kompakt, universell

### 6. Schutzschaltungen  
- Sicherungen  
- TVS-Dioden  
- Verpolschutz  
- Strombegrenzung  

## Grundgleichungen  

### Leistung  
P = U × I  

### Wirkungsgrad eines Netzteils  
η = P_out / P_in  

### Glättungskondensator  
ΔU ≈ I_load / (f × C)

### Buck-Regler  
V_out = D × V_in  
(D = Duty-Cycle)

## Abhängigkeiten  
- electricity_basic  
- electronics_diode_basic  
- electronics_capacitor_basic  
- electronics_inductor_basic  
- electronics_transistor_basic  
- heat_transfer_basic  

## Mechanismus  
1. Eingangsenergie wird umgewandelt (AC → DC oder DC → stabilisiertes DC)  
2. Ripple wird durch Kondensatoren reduziert  
3. Regler stabilisiert Spannung trotz schwankender Last  
4. Schutzschaltungen verhindern Schäden  
5. Energie wird an Lasten verteilt  

## Kombinierbarkeit  
- Mikrocontroller & Sensorik  
- Motorsteuerungen  
- Audioelektronik  
- Funkmodule  
- Batterieladeschaltungen  
- Industriesteuerungen  
- Embedded Systeme  

## Beispiele  
- 5V-USB-Netzteil  
- PC-Netzteil (ATX)  
- Li-Ion-Batterielader  
- Step-Down-Regler für LED-Lampen  
- Netzteil für CNC-/3D-Drucker  

## Visualisierung (textuell)  
Quelle → Gleichrichter → Glättung → Regler → Last  

## Vorteile  
- stabile Versorgung  
- universell einsetzbar  
- Schutz vor Überspannung / Überstrom  

## Nachteile  
- Effizienzverluste (besonders bei LDOs)  
- Schaltregler erzeugen EM-Störungen  
- zusätzliche Bauteilkomplexität  

## Quellen  
- Netzteiltechnik Grundlagen  
- Leistungselektronik  
- Anwendungshinweise von TI, ST, Infineon
