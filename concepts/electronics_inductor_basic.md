# Modul: Grundlegende Induktivitäten (Inductors)  
ID: electronics_inductor_basic  
Kategorie: Elektronik / Passive Bauelemente  
Version: 1.0

## Funktion  
Speicherung von Energie im Magnetfeld eines stromdurchflossenen Leiters.  
Grundlage für Transformatoren, Motoren, Filter, Schaltnetzteile und HF-Technik.

## Prinzip  
Eine Induktivität erzeugt ein Magnetfeld proportional zum Stromfluss.  
Änderungen des Stroms induzieren eine Spannung, die der Änderung entgegenwirkt (Lenz’sche Regel).

## Inputs  
- Strom  
- Frequenz  
- Induktivität (L)  
- Kernmaterial (Luft, Ferrit, Eisen)  
- Wicklungsparameter  

## Outputs  
- induzierte Spannung  
- magnetische Energie  
- Blindwiderstand  
- Stromverzögerung  

## Grundgleichungen  

### Induktivität  
E = ½ L I²  

### Induzierte Spannung  
U_ind = L × (dI/dt)

### Blindwiderstand (AC)  
X_L = 2π f L  

### Stromanstieg bei RL-Ladung  
I(t) = I_max × (1 – e^(–tR/L))

## Typen von Induktivitäten  
- Luftspulen  
- Ferritkernspulen  
- Eisenpulverkerne  
- Transformatoren (gewickelte Kopplung)  
- Drosseln  
- HF-Induktivitäten  

## Abhängigkeiten  
- electricity_basic  
- electronics_resistor_network_basic  
- electronics_capacitor_basic  
- energy_conversion_basic  
- dynamics_basic (Motoren)  

## Mechanismus  
1. Strom fließt → Magnetfeld entsteht  
2. Änderung des Stroms → induzierte Spannung  
3. Energie wird im Magnetfeld gespeichert  
4. Spule wirkt als frequenzabhängiges Element  
5. In Kombination mit Kondensatoren entstehen Schwingkreise  

## Kombinierbarkeit  
- LC-Filter (Hochpass, Tiefpass, Bandpass)  
- Transformatoren (gegenseitige Induktion)  
- DC/DC-Schaltregler  
- Motoren (Rotorfeld)  
- Zündspulen  
- Funktechnik & Antennen  
- Energiespeicherung beim Abschalten von Lasten  

## Beispiele  
- 50 Hz Transformator  
- Ferrit-Induktivität in Schaltnetzteilen  
- Resonanzkreis im Radio  
- Entstördrossel  
- Motorspule im Elektromotor  
- Relais (Induktionsspule)  

## Visualisierung (textuell)  
Strom ↑ → Magnetfeld ↑ → Energie gespeichert  
Strom ↓ → Spannung wird induziert (dI/dt entgegenwirken)  

## Vorteile  
- effiziente Energiespeicherung  
- unverzichtbar für Transformatoren & Filter  
- sehr hohe Stromtragfähigkeit möglich  

## Nachteile  
- groß und schwer bei niedriger Frequenz  
- EM-Störungen bei schnellen Schaltvorgängen  
- Sättigung des Kernmaterials bei hohen Strömen  

## Quellen  
- Grundlagen der Elektrotechnik II  
- Magnetismus & Induktion  
- Schaltnetzteile und Transformatorenlehre
