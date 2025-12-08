# Modul: Grundlegende Kondensatoren (Capacitors)  
ID: electronics_capacitor_basic  
Kategorie: Elektronik / Passive Bauelemente  
Version: 1.0

## Funktion  
Speicherung elektrischer Ladung und Glättung, Filterung sowie zeitabhängige Reaktionen in Schaltungen.  
Grundbaustein von Netzteilen, Filtern, Oszillatoren, Energiespeichern und Digitaltechnik.

## Prinzip  
Ein Kondensator speichert Energie im elektrischen Feld zwischen zwei leitenden Platten, getrennt durch ein Dielektrikum.

Kapazität beschreibt die Fähigkeit, Ladung pro Volt zu speichern.

## Inputs  
- Spannung  
- Kapazität (C)  
- Dielektrikumstyp  
- Frequenz  
- Umgebungstemperatur

## Outputs  
- Ladung  
- Reaktanz (Xc)  
- zeitabhängige Spannungs- oder Stromkurven  
- geglättete oder gefilterte Signale  

## Grundgleichungen  

### Kapazität  
C = ε × A / d  

### Ladung  
Q = C × U  

### Energie  
E = ½ C U²  

### Reaktanz (Wechselstrom)  
Xc = 1 / (2π f C)  

### Verhalten im Zeitbereich (RC-Ladung/Entladung)  
U(t) = U₀ (1 – e^(–t/RC))  
U(t) = U₀ e^(–t/RC)

RC = Zeitkonstante

## Kondensatortypen  
- Keramikkondensator  
- Elektrolyt-Kondensator  
- Folienkondensator  
- Tantal  
- Superkondensator (ultrahohe Kapazität)  

## Abhängigkeiten  
- electricity_basic  
- electronics_resistor_network_basic (RC-Netzwerke)  
- energy_conversion_basic  
- heat_transfer_basic  

## Mechanismus  
1. Spannung wird angelegt  
2. Elektrisches Feld baut sich auf  
3. Ladung wird gespeichert  
4. Kondensator reagiert verzögert und gibt Energie ab  
5. In Wechselstromschaltungen wirkt er als frequenzabhängiges Element  

## Kombinierbarkeit  
- RC-Tiefpass und Hochpass  
- Glättung in Netzteilen  
- Zeitgeber  
- Schwingkreise (LC)  
- Entstörung  
- Energiespeicher  
- Gleichspannungsblocker  
- Mikrofonkapseln (Elektret)  

## Beispiele  
- Kondensator nach Gleichrichter → glättet Spannung  
- RC-Timer → erzeugt Verzögerung  
- LC-Filter → Radiotechnik  
- Supercaps → kurzzeitige Energiepuffer  
- Hochpass für Audiosignale  

## Visualisierung (textuell)  
Quelle → Kondensator → lädt/entlädt → beeinflusst Frequenzen & Zeitverhalten  

## Vorteile  
- einfache Bauteile  
- enorm vielseitig  
- essenziell für Stabilität und Filterung  
- speichern Energie effizienter als reine Widerstandsnetzwerke

## Nachteile  
- Polarität bei Elektrolyt-Typen  
- Kapazitätsdrift bei Temperatur  
- begrenzte Lebensdauer (Elektrolyte)  
- Spannungsgrenzen beachten  

## Quellen  
- Grundlagen der Elektrotechnik  
- Elektronik: passive Bauelemente  
- RC- und LC-Netzwerkanalyse
