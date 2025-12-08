# Modul: Pneumatik — Grundprinzip (mech_pneumatics_basic)

## Kategorie
Mechanische Energieübertragung – Fluidtechnik (Pneumatik)

## Funktion
Erzeugung, Übertragung und Steuerung von Kraft und Bewegung durch komprimierte Luft.

## Prinzip
Luft ist kompressibel → Energie wird in Form von Druckluft gespeichert.  
Bewegung entsteht durch Druckdifferenzen, die Kolben oder Membranen antreiben.

## Inputs
- Druckluft (Kompressor, Speicher)
- pneumatische Steuerung
- mechanische Rückstellung (Feder oder Gegenkolben)

## Outputs
- schnelle lineare Bewegung
- wiederholbare Hubzyklen
- Schalt- oder Klemmkraft
- Druck- und Strömungsenergie

## Typische Anwendungen
- Automatisierung (Greifer, Schieber)
- Verpackungsmaschinen
- Pick-and-Place Robotik
- Pneumatische Zylinder aller Art
- Sprühtechnik
- Türmechanismen (Bus-/Zugtüren)
- medizinische Geräte

## Abhängigkeiten
- mech_cylinder_basic
- energy_conversion_basic
- mech_valve_basic (kommt später)
- starter_mechanisms

## Mechanismus
1. Kompressor erzeugt Druckluft.  
2. Druckluft gelangt über Ventile zum Arbeitszylinder.  
3. Druck wirkt auf Kolbenfläche → Bewegung entsteht.  
4. Abluft strömt über Auslassventile ab.  
5. Zylinder kehrt durch Feder oder Gegenluft zurück.

## Kombinierbarkeit
- Greif- und Aktuator-Systeme
- schnelle Schaltvorgänge
- Klemm- und Spannmechanik
- Zyklen mit hoher Wiederholrate
- Pick-and-Place-Automation
- Maschinensteuerung

## Beispiele
- Pneumatikzylinder in Fabriken
- Druckluft-betriebene Werkzeuge
- Lackiergeräte
- Bus- und Zugtüren
- Labor-Automatisierung

## Visualisierung (textuell)
Kompressor → Druckspeicher → Ventil → Zylinder → Kolbenbewegung → Abluft.

## Vorteile
- sehr schnelle Bewegungen
- hohe Wiederholgenauigkeit
- günstige Komponenten
- sauber (keine Flüssigkeiten)
- sicher (Luft als Medium)

## Nachteile
- geringere Kräfte als Hydraulik
- kompressibel → geringere Präzision
- lauter (Kompressor)
- Energieverlust durch Kompression & Abluft

## Quellen
- Grundlagen Pneumatik (Fluidtechnik)
- ISO 5599 Ventiltechnik
- Maschinenbau-Lehrbücher Pneumatik
