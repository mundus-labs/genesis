# Modul: Hydraulik — Grundprinzip (mech_hydraulics_basic)

## Kategorie
Mechanische Energieübertragung – Fluidtechnik (Hydraulik)

## Funktion
Übertragung von Kraft und Bewegung durch inkompressible Flüssigkeiten (meist Öl).

## Prinzip (Pascal’sches Gesetz)
Druck in einer eingeschlossenen Flüssigkeit verteilt sich gleichmäßig in alle Richtungen.

p = F / A  
(Druck = Kraft / Fläche)

→ Kleine Kraft auf kleiner Fläche erzeugt große Kraft auf großer Fläche.

## Inputs
- mechanische Kraft
- Bewegungsenergie
- Antrieb (Handpumpe, Motorpumpe)
- Hydraulikflüssigkeit

## Outputs
- verstärkte Kraft
- lineare Bewegung
- Druck
- präzise gesteuerte Belastungen

## Typische Anwendungen
- Auto-Bremsanlagen  
- Hydraulikpressen  
- Bagger, Lader, Baumaschinen  
- Aufzugsysteme  
- Lenkanlagen  
- Flugzeugsteuerung  
- Werkstattheber (Wagenheber)  

## Abhängigkeiten
- mech_cylinder_basic  
- energy_conversion_basic  
- mech_fluid_basic (optional – kommt später)
- starter_mechanisms

## Mechanismus
1. Pumpe erzeugt Druck in einem geschlossenen System.  
2. Druck wirkt auf Kolbenflächen (p = F/A).  
3. Bewegung des Arbeitszylinders führt Kraft oder Hub aus.  
4. Rücklauf über Ventile steuert Flussrichtung.  
5. System arbeitet nahezu verlustfrei durch geringe Kompressibilität des Öls.

## Kombinierbarkeit
- Kraftverstärkungssysteme  
- Robotik-Greifer  
- Hebesysteme  
- Federersatzsysteme  
- hydraulische Kinematiken  
- Energiepuffer (mit Akkumulatoren)  

## Beispiele
- Werkstatt-Wagenheber  
- Pressen (20t, 50t, 100t)  
- Bagger-Ausleger  
- Hydrauliklenkung  
- Aufzüge (Ölkolben)  

## Visualisierung (textuell)
Kraft → Pumpe → Druckleitung → Zylinder → Kolben bewegt sich → Hub oder Kraftausführung.

## Vorteile
- enorme Kraftverstärkung  
- präzise Regelung möglich  
- sehr robust  
- große Lasten bewegbar  
- gleichmäßige Kraftübertragung  

## Nachteile
- Öl-Leckagen möglich  
- Temperaturabhängigkeit der Viskosität  
- regelmäßige Wartung erforderlich  
- Gefahr hoher Drücke  

## Quellen
- Pascal’sches Gesetz  
- DIN ISO 4413 Fluidtechnik  
- Grundlagen Hydraulik – Maschinenbau-Lehrbücher
