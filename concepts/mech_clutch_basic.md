# Modul: Grundlegende Kupplungsmechanik (Clutch Mechanism)  
ID: mech_clutch_basic  
Kategorie: Mechanik / Krafttrennung & Antriebssteuerung  
Version: 1.0

## Funktion  
Selektives Koppeln oder Trennen zweier rotierender Systeme zur Kontrolle von Kraftfluss, Drehmoment und Bewegung.

## Prinzip  
Eine Kupplung verbindet zwei Wellen bei Bedarf kraftschlüssig oder formschlüssig.  
Durch Reibung, positive Verzahnung oder magnetische Kräfte kann Drehmoment übertragen oder unterbrochen werden.

## Inputs  
- Drehmoment  
- Drehbewegung  
- Steuerimpuls (mechanisch, hydraulisch, elektrisch)  

## Outputs  
- gekoppelter oder entkoppelter Kraftfluss  
- kontrolliertes Anfahren oder Stoppen  
- geregelte Drehmomentübertragung  

## Kupplungsarten  
- Reibkupplung (KFZ-Kupplung)  
- Lamellenkupplung  
- Klauenkupplung (Formschluss)  
- Magnetkupplung  
- Fliehkraftkupplung  
- Hydrodynamische Kupplung  

## Abhängigkeiten  
- mech_bearing_basic  
- mech_gear_basic  
- mech_transmission_basic  

## Mechanismus  
1. Zwei Wellen sind trennbar gelagert  
2. Aktivierung erzeugt Reibschluss, Formschluss oder Magnetkraft  
3. Drehmoment wird schrittweise oder sofort übertragen  
4. Lösen der Kupplung trennt die Systeme wieder  

## Kombinierbarkeit  
- Schaltgetriebe  
- Roboterantriebe  
- Werkzeugmaschinen  
- Fahrzeugantriebe  
- Sicherheitsmechanismen (Überlastkupplung)  

## Beispiele  
- Kupplungspedal im Auto  
- Magnetkupplung in Klimakompressoren  
- Fliehkraftkupplung in Scootern  
- Sicherheitskupplung in CNC-Fräsen  
- Einwegkupplung bei E-Bike-Naben  

## Visualisierung (textuell)  
Welle A ↔ (Kupplung) ↔ Welle B  
→ Kraftfluss ein/aus  
→ Drehmoment steuerbar

## Quellen  
- Fundamentals of Clutch & Power Transmission  
- Open Mechanical Drive Resources
