# Modul: Grundlegende Gelenkmechaniken (Joint Mechanisms)  
ID: mech_joint_basic  
Kategorie: Mechanik / Bewegungsführung  
Version: 1.0

## Funktion  
Verbindung zweier Bauteile, die eine definierte relative Bewegung erlauben:  
Rotation, Translation oder eine Kombination daraus.

## Prinzip  
Ein Gelenk limitiert Bewegungen gezielt und ermöglicht bestimmte Freiheitsgrade (Degrees of Freedom – DoF).

## Inputs  
- mechanische Lasten  
- Drehmomente  
- Bewegungsimpulse  

## Outputs  
- kontrollierte Bewegung  
- definierte Freiheitsgrade  
- Kraftübertragung in gewünschter Richtung  

## Typische Gelenktypen  
### 1. Drehgelenk (Revolute Joint)  
- 1 DoF: Rotation  
- Beispiel: Türscharnier  

### 2. Schub- oder Prismatic Joint  
- 1 DoF: Translation  
- Beispiel: Schlittenführung  

### 3. Kugelgelenk (Spherical Joint)  
- 3 DoF: Rotation in alle Richtungen  
- Beispiel: Auto-Spurgelenk, Hüftgelenk  

### 4. Zylindergelenk  
- 2 DoF: Rotation + Translation  
- Beispiel: Teleskopmechanismen  

### 5. Kardangelenk / Universal Joint  
- 2 DoF: gekreuzte Rotationsachsen  
- Beispiel: Antriebswellen  

### 6. Planargelenk  
- 3 DoF: 2 Translationen + Rotation in Ebene  
- Beispiel: Schiebebühnen  

## Abhängigkeiten  
- mech_bearing_basic  
- mech_linkage_basic  
- mech_transmission_basic  

## Mechanismus  
1. Gelenk verbindet Bauteile, die relativ zueinander bewegt werden sollen  
2. Freiheitsgrad(e) abhängig von der Geometrie  
3. Kraft wird nur in definierten Richtungen übertragen  
4. Lagerung bestimmt Reibung und Stabilität  

## Kombinierbarkeit  
- Robotergelenke  
- Fahrwerksmechanik  
- Hebelmechanismen  
- Steuer- und Regelmechanik  
- Aktuatorsysteme  
- Getriebe und Kurvenmechaniken  

## Beispiele  
- Türscharnier (einfaches Drehgelenk)  
- Roboterarm-Gelenke  
- Auto-Antriebswellen (Kardangelenke)  
- Kugelgelenke in Aufhängungen  
- Teleskopauszüge (Zylindergelenk)  

## Visualisierung (textuell)  
Teil A —(Gelenk)— Teil B  
→ definiert erlaubte Bewegungen  
→ blockiert unerwünschte Bewegungen  

## Vorteile  
- definierte Bewegungskontrolle  
- geringes Spiel (je nach Gelenkart)  
- weit verbreitet und gut verstanden  

## Nachteile  
- Verschleiß an Gelenkflächen  
- Schmierung oft notwendig  
- Spiel/Backlash bei günstigen Bauformen  

## Quellen  
- Kinematik der Maschinen  
- Maschinenbau-Grundlagen (Joints & DoF)
