# Modul: Grundlegender Zylinder- und Kolbenmechanismus (Cylinder Mechanism)  
ID: mech_cylinder_basic  
Kategorie: Mechanik / Linearantrieb  
Version: 1.0

## Funktion  
Erzeugt lineare Bewegung oder Kraft durch Druckdifferenzen (Hydraulik/Pneumatik) oder durch mechanische Führung von Kolben in Zylindern.

## Prinzip  
Ein Kolben bewegt sich in einem zylindrischen Gehäuse.  
Druck wirkt auf die Kolbenfläche → Kraft entsteht:

F = p × A  
(Kraft = Druck × Fläche)

Auch rein mechanische Zylinder existieren (Federzylinder, Gasdruckfeder, Dämpfer).

## Inputs  
- Druck (hydraulisch oder pneumatisch)  
- mechanischer Rückhub (Feder, Gegenluft, Gegenkraft)  
- Führungskräfte  

## Outputs  
- lineare Bewegung  
- Hub  
- Kraft in axialer Richtung  

## Zylindertypen  
### 1. Einfachwirkender Zylinder  
- Druck nur in einer Richtung  
- Rückstellung durch Feder  

### 2. Doppelwirkender Zylinder  
- Druck auf beiden Seiten  
- bidirektionale Kraft  

### 3. Teleskopzylinder  
- mehrere Stufen  
- großer Hub auf kleinem Bauraum  

### 4. Gasdruckzylinder  
- Stickstoffdruck + Federcharakteristik  

### 5. Dämpferzylinder  
- viskoser Widerstand als Bewegungsbegrenzung  

## Abhängigkeiten  
- mech_hydraulics_basic  
- mech_pneumatics_basic  
- mech_joint_basic  
- mech_friction_basic  
- starter_mechanisms  

## Mechanismus  
1. Druck wird in den Zylinder geleitet  
2. Kolbenfläche erfährt Kraft  
3. Kolben bewegt sich linear  
4. Abdichtung (Dichtungen) hält Druck getrennt  
5. Führung verhindert Verkanten  
6. Rückhub durch Druck, Feder oder Schwerkraft  

## Kombinierbarkeit  
- Hydrauliksysteme  
- Pneumatikzylinder  
- Robotik-Aktuatoren  
- industrielle Pressen  
- Fahrzeugbremsen  
- Hubsysteme und Aufzüge  

## Beispiele  
- Bagger-Armzylinder  
- Hubtischzylinder  
- pneumatische Greifer  
- Stoßdämpfer (Dämpferzylinder)  
- Gasdruckfeder in Kofferraumdeckeln  

## Visualisierung (textuell)  
Druck → Kolbenfläche → Kraft → Hub → lineare Bewegung  

## Vorteile  
- hohe Kraft möglich (Hydraulik)  
- schnelle Bewegung (Pneumatik)  
- robuste Bauformen  
- viele Baugrößen und Varianten  

## Nachteile  
- Leckage (Hydraulik)  
- kompressible Luft vermindert Präzision (Pneumatik)  
- regelmäßige Wartung notwendig  

## Quellen  
- Fluidtechnik Grundlagen  
- Maschinenbau Kolben-Zylinder-Systeme
