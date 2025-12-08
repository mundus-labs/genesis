# Modul: Grundlegender Seilzug- und Umlenkmechanismus (Pulley Mechanism)  
ID: mech_pulley_basic  
Kategorie: Mechanik / Kraftumlenkung & Übersetzung  
Version: 1.0

## Funktion  
Umlenkung von Kräften und Bewegungen sowie Erzeugung eines mechanischen Vorteils (Kraftgewinn) durch den Einsatz von Rollen und Seilen.

## Prinzip  
Eine feste oder lose Rolle ändert Richtung oder Betrag der Kraft.  
Mehrere Rollen in Kombination bilden einen Flaschenzug → Kraftübersetzung steigt proportional zur Anzahl tragender Seilstränge.

## Inputs  
- Zugkraft  
- Seilbewegung  
- mechanische Last  

## Outputs  
- geänderte Kraftrichtung  
- erhöhte oder verringerte Kraft  
- veränderte Geschwindigkeit der Last  

## Rollentypen  
- feste Rolle (nur Umlenkung)  
- lose Rolle (Kraftgewinn)  
- kombinierte Flaschenzüge  
- Seilwinden  
- Mehrfachrollen (Reduzierung der Lastbewegungsgeschwindigkeit)

## Abhängigkeiten  
- starter_mechanisms  
- mech_linkage_basic  
- mech_transmission_basic  

## Mechanismus  
1. Seil über Rolle geführt → Richtung der Kraft ändert sich  
2. Lose Rollen halbieren die notwendige Kraft  
3. Kraftübersetzung:  
   - F_out = F_in × n_tragende_Stränge  
4. Bewegung:  
   - v_Load = v_in / n  
5. Hohe Effizienz bei geringer Reibung

## Kombinierbarkeit  
- Hebezeuge (Krane, Aufzüge)  
- Fitnessgeräte  
- Bühnen- und Bühnentechnik  
- Segelmechanik  
- Rettungssysteme  
- mechanische Übersetzungen in Werkstätten  

## Beispiele  
- Baukran mit Flaschenzug  
- Segel-Umlenkrollen  
- Garagentor-Federseilzug  
- einfache Lastenheber  
- Höhenrettung und Sicherungstechnik  

## Visualisierung (textuell)  
Input: Zugkraft  
→ Rolle (Umlenkung)  
→ mehrere Rollen (Übersetzung)  
→ Last bewegt sich kontrolliert

## Vorteile  
- erheblicher Kraftgewinn möglich  
- einfache Mechanik  
- leicht und modular kombinierbar  
- ideal für große Lasten  

## Nachteile  
- Seildehnung reduziert Präzision  
- Reibungsverluste an Rollen  
- Geschwindigkeit sinkt proportional zur Kraftverstärkung  

## Quellen  
- Grundlagen der Hebe- und Fördertechnik  
- Open Mechanical Transmission Resources
