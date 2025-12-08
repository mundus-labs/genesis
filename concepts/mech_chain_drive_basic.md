# Modul: Grundlegender Kettenantrieb (Chain Drive Mechanism)  
ID: mech_chain_drive_basic  
Kategorie: Mechanik / Kraft- & Bewegungsübertragung  
Version: 1.0

## Funktion  
Übertragung von Drehmoment und Bewegung über größere Distanzen mithilfe einer formschlüssigen Kette und zweier (oder mehr) Kettenräder.  
Hohe Belastbarkeit, kein Schlupf, sehr robuste Kraftübertragung.

## Prinzip  
Zähne des Kettenrads greifen in die Kettenglieder ein → formschlüssige Übertragung.  
Übersetzungsverhältnis ergibt sich aus der Zähnezahl der Räder.

## Inputs  
- Drehmoment  
- Drehbewegung  

## Outputs  
- synchronisierte Drehbewegung auf zweitem Kettenrad  
- veränderte Drehzahl / Kraft (Übersetzung)  

## Typische Kettenarten  
- Rollenkette (Standard)  
- Zahnkette / Silent Chain  
- Hülsenkette  
- Duplex / Triplex (mehrreihige Ketten)  

## Abhängigkeiten  
- mech_gear_basic  
- mech_bearing_basic  
- mech_transmission_basic  

## Mechanismus  
1. Antriebskettenrad dreht sich  
2. Kettenglieder greifen formschlüssig ein  
3. Kette überträgt Zugkräfte → kein Schlupf  
4. Abtriebskettenrad bewegt sich synchron  
5. Übersetzung:  
   - i = Z₂ / Z₁ (Z = Zähnezahl)

## Kombinierbarkeit  
- Hochlast-Antriebe  
- Fahrradmechanik  
- Motorradantriebe  
- Fördertechnik  
- Robotik (synchrone Achsen)  
- Werkzeugmaschinen  

## Beispiele  
- Fahrradkette  
- Motorrad-Kettenantrieb  
- Förderbänder  
- Industriegetriebeketten  
- Kettentriebe in Motoren (z. B. Steuerkette)

## Visualisierung (textuell)  
Kettenrad A → Kette → Kettenrad B  
→ kein Schlupf, formschlüssige Übertragung

## Vorteile  
- hohe Belastbarkeit  
- schlupffrei  
- gute Effizienz  
- weit gespannte Achsabstände möglich  
- langlebig bei guter Schmierung  

## Nachteile  
- Verschleiß an Kette und Ritzeln  
- regelmäßige Schmierung nötig  
- Geräusche unter Last  
- längt sich mit der Zeit („Kettenstretch“)  

## Quellen  
- Open Power Transmission Resources  
- Fundamentals of Chain Drive Engineering
