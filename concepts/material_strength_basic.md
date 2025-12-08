# Modul: Grundlegende Material- und Festigkeitslehre (Material Strength)  
ID: material_strength_basic  
Kategorie: Physik / Mechanik der Werkstoffe  
Version: 1.0

## Funktion  
Vorhersage, wie Materialien auf Kräfte reagieren:  
Zug, Druck, Biegung, Torsion, Schub.  
Ziel: Feststellen, ob ein Bauteil hält oder versagt.

## Prinzip  
Materialien deformieren sich unter Last.  
Verhalten wird durch Spannungen (σ, τ) und Dehnungen (ε, γ) beschrieben.  
Versagen tritt ein, wenn Spannungen die Materialgrenze überschreiten.

## Inputs  
- äußere Kräfte  
- Momente (Biegemoment, Torsionsmoment)  
- Materialparameter  
- Geometrie (Querschnitt)  

## Outputs  
- Spannungsverteilung  
- Verformung  
- Sicherheitsfaktoren  
- Bruch oder plastische Deformation  

## Grundgrößen  

### 1. Spannung (σ)  
σ = F / A  
Kraft pro Fläche.

### 2. Dehnung (ε)  
ε = ΔL / L  
Relative Längenänderung.

### 3. Schubspannung (τ)  
τ = F_tangential / A  

### 4. Elastizitätsmodul (E)  
Steifheit des Materials.

### 5. Streckgrenze / Zugfestigkeit  
Maximale Spannung vor bleibender Deformation oder Bruch.

## Belastungsarten  
- Zug  
- Druck  
- Biegung  
- Torsion  
- Schub  

## Abhängigkeiten  
- mech_joint_basic  
- mech_linkage_basic  
- energy_conversion_basic  
- heat_transfer_basic (Materialverhalten temperaturabhängig)

## Mechanismus  
1. Kraft wirkt auf Bauteil  
2. Spannung entsteht → Material verformt sich  
3. Elastischer Bereich: reversible Verformung  
4. Plastischer Bereich: dauerhafte Deformation  
5. Bruch, wenn Belastung > Materialfestigkeit  

## Kombinierbarkeit  
- mechanische Konstruktionen  
- Tragwerke  
- Maschinenbau  
- Robotik  
- Fahrzeugtechnik  
- Pumpen und Zylinder  
- Dampfkessel / Druckbehälter (Sicherheitsberechnung)

## Beispiele  
- Stahlträger unter Biegung  
- Achse unter Torsion  
- Hydraulikzylinder unter Druck  
- Schrauben unter Zuglast  
- Flugzeugtragflächen unter wechselnden Lasten  

## Visualisierung (textuell)  
Kraft → Spannung → Dehnung → ggf. Versagen  
Diagramm: Spannung–Dehnung-Kurve (elastisch → plastisch → Bruch)

## Vorteile  
- universelle anwendbare Theorie  
- bestimmt Sicherheit und Lebensdauer  
- integraler Bestandteil aller Konstruktionen  

## Nachteile  
- reale Werkstoffe haben komplexes Verhalten  
- Ermüdung (Wechselbelastung) schwer modellierbar  
- Temperatur- & Zeitabhängigkeit (Kriechen)  

## Quellen  
- Festigkeitslehre / Timoshenko  
- Maschinenbaumechanik Grundlagen  
- Materialwissenschaft (Werkstofftechnik)
