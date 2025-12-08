# Modul: Grundlegende Reibungsmechanik (Friction Mechanism)  
ID: mech_friction_basic  
Kategorie: Mechanik / Kontaktphysik  
Version: 1.0

## Funktion  
Reibung erzeugt Widerstand gegen relative Bewegung zwischen zwei Kontaktflächen.  
Sie kann Bewegung ermöglichen (z. B. Gehen, Kupplung) oder verhindern (Bremsen, Klemmung).

## Prinzip  
Reibungskraft entsteht durch mikroskopische Rauheiten und Adhäsion zwischen Oberflächen.  
Sie wirkt entgegengesetzt zur Bewegungsrichtung und hängt von der Normalkraft ab.

F = μ × N  
(Reibkraft = Reibkoeffizient × Normalkraft)

## Inputs  
- Normalkraft  
- relative Bewegung oder Bewegungstendenz  
- Materialpaarung  
- Oberflächenrauheit  

## Outputs  
- Reibkraft  
- Energieverlust (Wärme)  
- Bewegungsbegrenzung oder Bewegungsermöglichung  

## Reibungsarten  
### 1. Haftreibung (static friction)  
- verhindert die Bewegung  
- größer als Gleitreibung  

### 2. Gleitreibung (kinetic friction)  
- wirkt während der Bewegung  
- F_kin < F_static  

### 3. Rollreibung  
- viel kleiner als Gleitreibung  
- abhängig von Deformation der Kontaktflächen  

### 4. Fluidreibung  
- bei geschmierten oder hydrodynamischen Systemen  

## Abhängigkeiten  
- mech_bearing_basic  
- mech_damper_basic  
- mech_joint_basic  
- mech_brake_basic  

## Mechanismus  
1. Kontaktflächen interagieren über Adhäsion + Rauheit  
2. Normalkraft bestimmt Reibkraft  
3. Energie wandelt sich in Wärme um  
4. Reibung kontrolliert Geschwindigkeit, Kraftfluss und Stabilität  

## Kombinierbarkeit  
- Bremsen  
- Kupplungen  
- Lager  
- Antriebssysteme  
- Robotik-Greifer  
- Klemmmechaniken  
- Fördertechnik  

## Beispiele  
- Autoreifen auf Asphalt  
- Bremsbelag auf Bremsscheibe  
- Schraube im Gewinde (Haftreibung)  
- Gleitlager  
- Schuhe auf Boden (Gehen)  

## Visualisierung (textuell)  
Bewegung → Kontaktfläche → μ × N → Reibkraft → Wärme  

## Vorteile  
- ermöglicht Kraftübertragung ohne Formschluss  
- einfache, robuste Mechanik  
- kann Bewegungen stabilisieren  

## Nachteile  
- Energieverlust (Wärme)  
- Verschleiß  
- unzuverlässig bei Verschmutzung oder Feuchtigkeit  
- schwankende Reibungskoeffizienten  

## Quellen  
- Tribologie-Grundlagen  
- Maschinenbau: Reibung & Verschleiß  
- Engineering Friction Models
