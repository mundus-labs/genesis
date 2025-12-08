# Modul: Grundlegender Kurbel-Schubstangen-Mechanismus (Slider-Crank Mechanism)  
ID: mech_slider_crank_basic  
Kategorie: Mechanik / Bewegungswandler  
Version: 1.0

## Funktion  
Umwandlung von Rotationsbewegung in lineare Bewegung oder umgekehrt.  
Dies ist der Kernmechanismus von Motoren, Pumpen, Kompressoren und Pressen.

## Prinzip  
Eine rotierende Kurbel bewegt eine Schubstange, die einen Schieber oder Kolben linear führt.  
Geometrie bestimmt Hub und Kraftverhältnisse.

## Inputs  
- Rotationsbewegung  
- Drehmoment  

## Outputs  
- lineare Hubbewegung  
- Kraftimpulse in axialer Richtung  

## Typische Bestandteile  
- Kurbel (Crank)  
- Schubstange (Connecting Rod)  
- Kolben / Schieber (Slider)  
- Führung (z. B. Zylinder)  

## Abhängigkeiten  
- mech_bearing_basic  
- mech_linkage_basic  
- mech_screw_basic (optional, für Aktuationshybride)

## Mechanismus  
1. Kurbel dreht sich um einen festen Drehpunkt  
2. Schubstange überträgt die Drehbewegung auf einen Kolben  
3. Kolben führt lineare Bewegung aus  
4. Kraftverlauf ist nicht linear → abhängig vom Kurbelwinkel  
5. Umkehrpunkt = Totpunkt (OT/UT)

## Kombinierbarkeit  
- Verbrennungsmotoren  
- Dampfmaschinen  
- Kompressoren  
- Hydraulikpumpen  
- Linearantriebe in Robotik  
- Press- und Stanzmaschinen  
- alternative Aktuatorik (Kurbel + Feder, Kurbel + Dämpfer)

## Beispiele  
- Automotor (Kolbenmotor)  
- Fahrrad-Tretmechanismus (vereinfachte Form)  
- Kolbenkompressor  
- Presslufthammer  
- Pumpmechanik in Dosiergeräten  

## Visualisierung (textuell)  
Kurbel → Schubstange → Kolben  
Rotation → Hubbewegung

## Vorteile  
- hohe Kraftausbeute  
- einfache Mechanik  
- robust  
- präziser, wiederholbarer Hub  
- Energiezwischenspeicherung möglich (Schwungrad)

## Nachteile  
- nichtlineare Kraftverteilung  
- Totpunktverlust  
- Vibrationen bei hohen Drehzahlen  

## Quellen  
- Open Mechanical Design Resources  
- Grundlagen der Maschinenelemente
