# Modul: Grundlegende Operationsverstärker (Operational Amplifiers)  
ID: electronics_opamp_basic  
Kategorie: Elektronik / Analoge Systeme  
Version: 1.0

## Funktion  
Verstärkung, Filterung und Verarbeitung analoger Signale.  
Ein Op-Amp vergleicht zwei Eingangsspannungen und erzeugt ein verstärktes Ausgangssignal.

## Prinzip  
Operationsverstärker besitzen zwei Eingänge:  
- nicht-invertierend (+)  
- invertierend (–)  

Der Ausgang reagiert auf die Differenz beider Eingänge:  
V_out = A_OL × (V+ – V–)

A_OL = Leerlaufverstärkung (typisch > 100 000)

Feedback (Rückkopplung) bestimmt die tatsächliche Verstärkung und Funktion.

## Inputs  
- Eingangsspannungen  
- Versorgungsspannung (Single oder Dual Rail)  
- Rückkopplungsnetzwerk (Widerstände, Kondensatoren)  

## Outputs  
- verstärkte Signale  
- gefilterte Signale  
- integrierte/differenzierte Signale  
- Gleichspannungs- oder Wechselspannungsfunktionen  

## Grundkonfigurationen  

### 1. Spannungsverstärker (Non-Inverting)  
V_out = V_in × (1 + R2/R1)

### 2. Inverting Amplifier  
V_out = – V_in × (R2/R1)

### 3. Buffer (Voltage Follower)  
V_out = V_in  
(hohe Eingangsimpedanz, niedrige Ausgangsimpedanz)

### 4. Summierer  
V_out = – (R2/R1) × (V1 + V2 + ...)

### 5. Differenzverstärker  
V_out = (R2/R1) × (V2 – V1)

### 6. Integrator  
V_out = –(1/RC) ∫ V_in dt

### 7. Differentiator  
V_out = –RC × (dV_in/dt)

## Wichtige Begriffe  
- Rail-to-Rail  
- Slew Rate  
- Bandbreite (GBW)  
- Offsetspannung  
- Eingangsrauschen  
- Ausgangsstromfähigkeit  

## Abhängigkeiten  
- electricity_basic  
- electronics_resistor_network_basic  
- electronics_capacitor_basic  
- electronics_transistor_basic  
- heat_transfer_basic  

## Mechanismus  
1. Op-Amp vergleicht Eingangsdifferenz  
2. Verstärkung wird durch Feedback festgelegt  
3. Ausgang liefert verstärktes, invertiertes oder gefiltertes Signal  
4. Grenzen: Versorgungsspannung, Slew Rate, Bandbreite  

## Kombinierbarkeit  
- Audioverstärker  
- Sensor-Vorverstärker (z. B. Thermoelement, Photodiode)  
- Analogfilter (Butterworth, Chebyshev)  
- Regler (PID, Feedback-Systeme)  
- ADC-Front-Ends  
- Aktuatorsteuerungen  
- Messgeräte (Oszilloskope, Multimeter)  

## Beispiele  
- Mikrofonverstärker  
- Audio-Line-Level-Verstärker  
- Summierer in Mischpulten  
- Differenzverstärker für Strommessung  
- Integrator für Regelungstechnik  
- Anti-Alias-Filter vor ADC  

## Visualisierung (textuell)  
V+ – V– → Verstärkung → Ausgang folgt Feedbackgesetz  

## Vorteile  
- extrem flexibel  
- präzise analoge Verarbeitung  
- universell einsetzbar  
- hohe Eingangsimpedanz  

## Nachteile  
- begrenzte Bandbreite  
- Slew-Rate-Limit  
- Eingangsversatz und Rauschen  
- Versorgungsspannung begrenzt Ausgang  

## Quellen  
- Analog Electronics Fundamentals  
- Operational Amplifier Theory  
- Linear Circuit Analysis
