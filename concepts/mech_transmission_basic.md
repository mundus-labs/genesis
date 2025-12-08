# Modul: Mechanische Grundkraftübertragung  
ID: mech_transmission_basic  
Kategorie: Mechanik / Kraftübertragung  
Version: 1.0  

## Funktion  
Übertragen von Kraft und Bewegung zwischen zwei Komponenten durch ein mechanisches Medium.

## Prinzip  
Mechanische Energie (Drehung oder lineare Bewegung) wird von einem Antrieb über ein Kopplungselement auf ein anderes Bauteil übertragen.

## Inputs  
- mechanische Energie (Drehmoment oder lineare Kraft)  
- ggf. kontinuierlicher Antrieb (Motor, Kurbel, Feder, Gewicht)

## Outputs  
- übertragene Kraft  
- übertragene Bewegung (Rotation oder Translation)

## Typische Übertragungselemente  
- Welle  
- Riemen  
- Kette  
- Zahnradpaar  
- Reibkupplung  

## Abhängigkeiten  
- mech_lever_basic  
- starter_mechanisms  
- energy_conversion_basic (falls Antrieb elektrisch)

## Mechanismus  
1. Eingangskraft wirkt auf das Übertragungselement  
2. Element koppelt Input-Komponente mit Output-Komponente  
3. Energie wird übertragen, ggf. mit Übersetzung (Ratio)  
4. Verlustleistung entsteht durch Reibung

## Kombinierbarkeit  
- Getriebe (Zahnräder)  
- Kraftwandler (Hebel, Schnecke, Riemen)  
- Antriebsstränge (Motor → Getriebe → Achse)  
- Mechanische Module in Robotik, Automatisierung, Werkzeugmaschinen

## Beispiele  
- Fahrradkette (Kette + Ritzel)  
- Auto-Getriebe (Zahnräder + Kupplung)  
- Nähmaschinenmechanik  
- Förderbänder

## Visualisierung (textuell)  
Input-Welle → Übertragungselement → Output-Welle

## Quellen  
- Grundlagen Maschinenbau (OER)  
- Mechanik der Kraftübertragung — offene Lehrmaterialien
