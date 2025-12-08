# Modul: Grundlegende Dynamik (Dynamics)  
ID: dynamics_basic  
Kategorie: Physik / Mechanik  
Version: 1.0

## Funktion  
Analyse der Kräfte, Beschleunigungen und Bewegungen von Körpern.  
Ziel: Vorhersage von Bewegungsabläufen, Kräften und Belastungen in dynamischen Systemen.

## Prinzip  
Newton’s Gesetze definieren die Bewegung:

1. Trägheitsgesetz  
2. F = m × a  
3. Actio = Reactio  

Bewegung entsteht aus Kräften und Impulsen.

## Inputs  
- Masse  
- Kräfte  
- Momente  
- Anfangsgeschwindigkeiten  
- äußere Einflüsse (Dämpfung, Reibung, Federkraft)  

## Outputs  
- Beschleunigung  
- Geschwindigkeit  
- Weg  
- dynamische Belastungen  
- kinetische Energie  

## Grundgleichungen  

### Newtons 2. Gesetz  
F = m × a  

### Impuls  
p = m × v  

### Impulserhaltung  
Σp_vorher = Σp_nachher  

### Rotationsdynamik  
M = J × α  
(J = Trägheitsmoment, α = Winkelbeschleunigung)

### Kinetische Energie  
E_kin = ½ m v²  

### Schwingungsansatz (Feder-Dämpfer)  
m ẍ + c ẋ + k x = F(t)

## Dynamische Phänomene  
- Schwingungen  
- Resonanz  
- Dämpfung  
- Stoß / Impulsübertragung  
- instabile Bewegungen  
- Ungleichförmigkeit bei Mechanismen  

## Abhängigkeiten  
- mech_spring_basic  
- mech_damper_basic  
- mech_mass_basic (optional)  
- statics_basic  
- material_strength_basic  

## Mechanismus  
1. Kraft erzeugt Beschleunigung  
2. Geschwindigkeit und Weg folgen durch zeitliche Integration  
3. System reagiert abhängig von Masse, Dämpfung, Federkonstanten  
4. Energie wandert zwischen kinetisch, potenziell, dissipativ  

## Beispiele  
- Fahrzeugfederung  
- Kurbeltrieb in Motoren  
- Robotikbewegungen  
- Fliehkraftkupplungen  
- Maschinen mit Masse-Ungleichgewichten  

## Kombinierbarkeit  
- Schwingungssysteme  
- Motorensimulation  
- Hydraulik- und Pneumatikbewegungen  
- Getriebedynamik  
- Robotik-Kinematik  
- Vibrationskontrolle  

## Visualisierung (textuell)  
Kraft → Beschleunigung → Geschwindigkeit → Bewegung → dynamische Reaktionen  

## Vorteile  
- universell einsetzbar  
- Grundlage für Simulationen  
- unverzichtbar für bewegte Systeme  

## Nachteile  
- höhere Komplexität als Statik  
- realistische Modelle benötigen Dämpfung & Reibung  
- nichtlineare Systeme schwer analytisch lösbar  

## Quellen  
- Engineering Dynamics (Hibbeler / Meriam)  
- Technische Mechanik: Dynamik  
- Maschinenbau Schwingungslehre
