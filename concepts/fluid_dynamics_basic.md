# Modul: Grundlegende Strömungsmechanik (Fluid Dynamics)  
ID: fluid_dynamics_basic  
Kategorie: Physik / Strömungslehre  
Version: 1.0

## Funktion  
Beschreibung und Analyse der Bewegung von Flüssigkeiten und Gasen sowie der Kräfte, die dabei auftreten.

## Prinzip  
Strömungen werden durch Druckunterschiede, Schwerkraft oder äußere Kräfte erzeugt.  
Fluidverhalten hängt ab von:  
- Dichte  
- Viskosität  
- Temperatur  
- Geschwindigkeit  
- Geometrie des Strömungsraums

## Inputs  
- Druck  
- Geschwindigkeit  
- Temperatur  
- Strömungsquerschnitt  
- Fluidparameter (ρ, μ)

## Outputs  
- Strömungswiderstand  
- Durchflussrate  
- Druckverlust  
- Kräfte auf Bauteile  
- Turbulenz oder laminare Strömung  

## Grundgleichungen  
### 1. Kontinuitätsgleichung  
A₁ v₁ = A₂ v₂  
→ Massenerhaltung

### 2. Bernoulli-Gleichung  
p + ½ρv² + ρgh = konstant  
→ Verbindung zwischen Druck, Geschwindigkeit und Höhe

### 3. Navier–Stokes Gleichungen (vereinfacht)  
Beschreiben vollständige Fluidbewegungen, wichtig für Simulationen.

## Strömungsarten  
- Laminar (geordnet, niedrige Reynolds-Zahl)  
- Transitional  
- Turbulent (chaotisch, hohe Reynolds-Zahl)

Reynolds-Zahl:  
Re = ρvL / μ

## Abhängigkeiten  
- mech_hydraulics_basic  
- mech_pneumatics_basic  
- energy_conversion_basic  
- mech_valve_basic  

## Mechanismus  
1. Druckunterschied → Bewegung  
2. Fluid folgt Kontinuitätsgesetz  
3. Reibung und Turbulenz erzeugen Verluste  
4. Druckenergie ↔ Geschwindigkeit ↔ Höhenenergie tauschen sich aus  
5. Rohrgeometrie bestimmt Widerstand (Darcy-Weisbach)

## Kombinierbarkeit  
- Pumpen (hydraulisch / pneumatisch)  
- Ventile und Strömungsregelung  
- Kühlkreisläufe  
- Luft- und Wasserströmung in Fahrzeugen  
- Turbinen (Wasserkraft, Windkraft)  
- Kompressoren  
- Flugzeugprofile (Auftrieb)  

## Beispiele  
- Durchfluss in einem Rohr  
- Luftstrom über Tragflächen  
- Wasserstrahl aus einer Düse  
- Strömungsverluste in Hydraulikleitungen  
- Hochgeschwindigkeitsluft in Pneumatiksystemen  

## Visualisierung (textuell)  
Druckdifferenz → Strömung → Reibung/Verluste → Kräfte auf Wände und Bauteile  

## Vorteile  
- beschreibt nahezu alle realen Fluidphänomene  
- Grundlage für Hydraulik und Pneumatik  
- ermöglicht Energieoptimierung  
- universell einsetzbar  

## Nachteile  
- komplex (Navier–Stokes schwer analytisch lösbar)  
- Turbulenz schwer vorherzusagen  
- Simulation oft erforderlich  

## Quellen  
- Grundlagen der Strömungsmechanik  
- Bernoulli & Navier–Stokes  
- Maschinenbau-Strömungslehre
