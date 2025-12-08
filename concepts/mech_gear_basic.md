# Modul: Grundlegende Zahnradmechanik (Gear Mechanism)  
ID: mech_gear_basic  
Kategorie: Mechanik / Kraft- & Bewegungsübertragung  
Version: 1.0

## Funktion  
Übertragung von Drehmoment und Drehzahl zwischen zwei oder mehreren Wellen mittels formschlüssiger Verzahnung.

## Prinzip  
Zähne zweier Räder greifen ineinander → fortlaufende Kraftübertragung ohne Schlupf.  
Drehzahl- und Drehmomentverhältnisse ergeben sich aus der Zahnanzahl.

## Inputs  
- Drehbewegung  
- Drehmoment  
- Eingangsdrehzahl  

## Outputs  
- veränderte Drehzahl  
- verändertes Drehmoment  
- Drehrichtungsänderung (optional)  

## Typische Zahnradarten  
- Stirnrad  
- Kegelrad  
- Schneckenrad  
- Planetengetriebe  
- Innenverzahnung  
- Kronenrad  

## Abhängigkeiten  
- mech_linkage_basic  
- mech_transmission_basic  
- energy_conversion_basic  

## Mechanismus  
1. Zähne übertragen Kraft ohne Schlupf  
2. Zahnradpaar bildet konstantes Übersetzungsverhältnis  
3. Eingriff sorgt für synchrone Bewegung  
4. Verhältnis:  
   - Übersetzung i = Z₂ / Z₁  
   - Drehmoment M₂ = M₁ * i  
   - Drehzahl n₂ = n₁ / i  

## Kombinierbarkeit  
- Motorgetriebe  
- Robotergelenke  
- Uhrenmechanismen  
- Fahrzeugantriebe  
- Industriegetriebe  
- Präzisionspositionierung  

## Beispiele  
- Fahrrad-Gangschaltung (Planetengetriebe)  
- Automatikgetriebe  
- Uhrwerk  
- Aktuator-Untersetzungsgetriebe  
- Werkzeugmaschinen  

## Visualisierung (textuell)  
Input Gear → engages → Output Gear  
→ verändert Drehmoment & Drehzahl

## Quellen  
- Fundamentals of Gear Design  
- Open Mechanical Transmission Resources
