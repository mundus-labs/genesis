# Modul: Grundlegende Dämpfermechanik (Damper Mechanism)  
ID: mech_damper_basic  
Kategorie: Mechanik / Bewegungsdämpfung  
Version: 1.0

## Funktion  
Reduktion, Verzögerung oder Glättung von Bewegungen durch Dissipation mechanischer Energie.

## Prinzip  
Ein Dämpfer wandelt kinetische Energie in Wärme oder Reibverluste um.  
Er arbeitet typischerweise zusammen mit Federn oder Schwingelementen.

## Inputs  
- Bewegung (Translation / Rotation)  
- Geschwindigkeit  
- Kraftimpulse  

## Outputs  
- Widerstandskraft proportional zur Geschwindigkeit  
- Reduzierte Schwingweite  
- kontrollierte Abbremsung  

## Typische Elemente  
- hydraulischer Dämpfer  
- pneumatischer Dämpfer  
- viskoser Reibdämpfer (Öl / Silikon)  
- mechanischer Reibdämpfer  
- Gummidämpfer (viskoelastisch)  

## Abhängigkeiten  
- mech_spring_basic  
- mech_linkage_basic  
- energy_conversion_basic  

## Mechanismus  
1. Bewegung erzeugt relative Verschiebung  
2. Medium (Öl, Luft, Elastomer) erzeugt Widerstand  
3. Energie wird dissipiert → Temperaturanstieg  
4. Bewegung verlangsamt / stabilisiert  

## Kombinierbarkeit  
- Feder-Masse-Dämpfer-Systeme  
- Fahrwerksmechanik  
- Präzisionsmaschinen  
- Vibrationskontrolle  
- Robotik-Actuation  
- Rückstellmechanismen  

## Beispiele  
- Stoßdämpfer im Auto  
- Soft-Close-Türmechanismen  
- Rotationsdämpfer in Elektronik  
- Dämpfer in Prothesen  
- Schwingungsisolatoren  

## Visualisierung (textuell)  
Bewegung → Widerstand → Energieverlust → kontrollierte Bewegung

## Quellen  
- Open Mechanical Engineering Resources  
- Fundamentals of Vibration & Damping
