# Modul: Grundlegende Wärmeübertragung (Heat Transfer)  
ID: heat_transfer_basic  
Kategorie: Physik / Energie & Thermodynamik  
Version: 1.0

## Funktion  
Beschreibung, Analyse und Vorhersage des Wärmetransports zwischen Körpern oder Systemen durch Leitung, Konvektion und Strahlung.

## Prinzip  
Wärme fließt immer vom höheren zum niedrigeren Temperaturniveau.  
Es existieren drei grundlegende Mechanismen:

1. Wärmeleitung (Conduction)  
2. Konvektion (Convection)  
3. Wärmestrahlung (Radiation)

## Inputs  
- Temperaturdifferenz  
- Materialparameter  
- Geometrie  
- Strömungsgeschwindigkeit (Konvektion)  
- Emissionsgrad (Strahlung)

## Outputs  
- Wärmestrom  
- Temperaturverteilung  
- Energieverluste  
- thermische Belastung von Bauteilen  

## Mechanismen  

### 1. Wärmeleitung  
Fourier’s Gesetz:  
q = –k × A × (dT/dx)  
→ Wärme fließt durch feste Körper  

k = Wärmeleitfähigkeit (Material abhängig)

### 2. Konvektion  
Newton’sches Abkühlgesetz:  
q = h × A × (T_oberfläche – T_fluid)  
→ Wärmeübertragung über strömende Fluide

h = Wärmeübergangskoeffizient (abhängig von Strömungsdynamik)

### 3. Wärmestrahlung  
Stefan–Boltzmann-Gesetz:  
q = ε × σ × A × (T⁴ – T_umgebung⁴)

ε = Emissionsgrad  
σ = Konstante 5.67×10⁻⁸ W/m²K⁴

## Abhängigkeiten  
- fluid_dynamics_basic  
- energy_conversion_basic  
- material_strength_basic (optional)  
- thermal_systems_basic (später)

## Beispiele  
- Kühlung von Motoren  
- Wärmeabgabe eines Hydrauliksystems  
- Kühler / Radiatoren  
- Heizelemente  
- Luftkühlung in Elektronik  
- Solareinstrahlung  

## Kombinierbarkeit  
- Pumpensysteme  
- Kühlkreisläufe  
- Wärmetauscher  
- Isolationsmaterialien  
- Energiesysteme (Turbinen, Heizungen, Kompressoren)

## Visualisierung (textuell)  
T_hot → Wärmeleitung/Konvektion/Strahlung → T_cold  
→ kontinuierlicher Wärmestrom  

## Vorteile  
- beschreibt universelle physikalische Prozesse  
- Grundlage für thermisches Design  
- essentiell für Energieeffizienz  
- relevant für Maschinen, Gebäude, Elektronik  

## Nachteile  
- Strahlung hochgradig nichtlinear  
- Konvektion abhängig von turbulenten Strömungen  
- oft Simulation erforderlich  

## Quellen  
- Grundlagen der Thermodynamik  
- Heat Transfer Incropera & DeWitt  
- Maschinenbau: Thermische Systeme
