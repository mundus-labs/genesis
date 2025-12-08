# Modul: Grundlegende Fertigung (Manufacturing Fundamentals)  
ID: manufacturing_basic  
Kategorie: Produktionstechnik / Fertigungsprozesse  
Version: 1.0

## Funktion  
Beschreibt grundlegende Herstellungsverfahren, Toleranzen, Werkstoffanforderungen und Prozessketten.  
Ermöglicht der KI-Sandbox, Systementwürfe auf Herstellbarkeit, Kosten, Präzision und Realisierbarkeit zu prüfen.

## Prinzip  
Fertigung wandelt ein technisches Design über definierte Prozesse in ein physisches Produkt um.  
Jeder Prozess besitzt Grenzen: Materialeigenschaften, Genauigkeit, Größe, Energiebedarf, Werkzeugparameter.

## Inputs  
- CAD/Designparameter  
- Materialdefinition  
- Toleranzen  
- Stückzahlen  
- Fertigungsstrategie  
- Energiekosten & Prozessdaten  

## Outputs  
- herstellbare Bauteile  
- Fertigungsbeschränkungen  
- Produktionskosten  
- Prozesskette  
- Materialbedarf  
- Machbarkeitsanalyse  

## Hauptfertigungsprozesse  

### 1. Urformen  
- Gießen  
- 3D-Druck (Additive Manufacturing)  
- Sintern  
→ erzeugt Rohformen aus flüssigem/pulverförmigem Material.

### 2. Umformen  
- Walzen  
- Schmieden  
- Tiefziehen  
→ Formänderung ohne Materialverlust.

### 3. Trennen  
- Drehen  
- Fräsen  
- Bohren  
- Laser-/Wasserstrahlschneiden  
→ Material wird gezielt entfernt.

### 4. Fügen  
- Schweißen  
- Löten  
- Schrauben  
- Kleben  
→ Herstellung von Baugruppen.

### 5. Beschichten  
- Lackieren  
- Galvanisieren  
- Härten  
→ Funktionsoberflächen herstellen.

### 6. Montage & Qualitätssicherung  
- Bauteile zusammensetzen  
- messtechnische Überprüfung  
- Endkontrolle

## Fertigungsparameter  
- Toleranzen  
- Rauheit  
- Wandstärken  
- Mindestradien  
- Werkzeugwege  
- Schrumpfung (Guss, 3D-Druck)  
- Materialabhängige Prozessfenster  

## Abhängigkeiten  
- materials_basic  
- mechanics_basic (indirekt)  
- system_design_basic  
- simulation_basic  
- module_validation_basic  

## Mechanismus  
1. Design wird analysiert  
2. Fertigungsmethode wird zugeordnet  
3. KI prüft Material-Eignung  
4. Simulation optional: Wärme, Kräfte, Spannungen  
5. Toleranzen werden geprüft  
6. Prozesskette wird erstellt  
7. Kosten-/Zeitabschätzung  
8. Rückmeldung an Systemdesign oder HRM  

## Kombinierbarkeit  
- Rapid Prototyping  
- Serienfertigung  
- robotergestützte Montage  
- digitale Fertigungszwillinge  
- KI-basiertes Fertigungsrouting  
- Optimierung von Bauteilgeometrien (DFM – Design for Manufacturing)

## Beispiele  
- 3D-Druck eines Gehäuses → Additive Manufacturing  
- Fräsen einer Welle → Zerspanung  
- Schweißen einer Rahmenstruktur → Fügen  
- PCB-Fertigung → Subtraktiv + Fügen + Beschichten  

## Visualisierung (textuell)  
Design → Prozessauswahl → Fertigungsschritte → Bauteil → Montage → Produkt  

## Vorteile  
- reale Umsetzbarkeit  
- Kosten- und Zeitoptimierung  
- frühzeitige Machbarkeitsanalyse  
- Verbindung von virtueller Sandbox und physischer Welt  

## Nachteile  
- Fertigung erfordert große Datenmengen  
- Kostenabschätzung teilweise unpräzise  
- Prozessabhängigkeiten komplex  
- DFM-Regeln müssen gepflegt werden  

## Quellen  
- Fertigungsverfahren nach DIN 8580  
- Additive Manufacturing Standards  
- Metallbearbeitung & Zerspanung  
- Produktionsplanung & -steuerung (PPS)
