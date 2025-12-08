# Modul: Grundlegende Statik (Statics)  
ID: statics_basic  
Kategorie: Physik / Mechanik  
Version: 1.0

## Funktion  
Analyse von Kräften und Momenten an Körpern im Gleichgewicht.  
Ziel: bestimmen, ob ein System stabil, belastbar und ruhefähig ist.

## Prinzip  
Ein Körper ist im statischen Gleichgewicht, wenn:

1. Summe aller Kräfte = 0  
   ΣF = 0  

2. Summe aller Momente = 0  
   ΣM = 0  

Damit bewegt sich das System nicht und rotiert nicht.

## Inputs  
- äußere Kräfte  
- Momente  
- Masse / Gewichtskraft  
- Geometrie  
- Lagerpunkte / Auflagerarten  

## Outputs  
- Auflagerreaktionen  
- interne Kräfte  
- Momentenverteilung  
- Stabilitätsbewertung  

## Grundkonzepte  

### Kräfte  
- Druck  
- Zug  
- Scherkräfte  
- Reibungskräfte  
- Reaktionskräfte der Auflager

### Momente  
M = F × r  
(Drehmoment = Kraft × Hebelarm)

### Auflagerarten  
- Festlager (2 Reaktionskräfte)  
- Loslager (1 Reaktionskraft)  
- Einspannung (3 Reaktionsgrößen: Kräfte + Moment)

### Freiheitsgrade & Lagerreaktionen  
→ Zahl der Unbekannten bestimmt Lösbarkeit.

## Abhängigkeiten  
- material_strength_basic  
- mech_joint_basic  
- mech_linkage_basic  

## Mechanismus  
1. System wird freigeschnitten (Free Body Diagram)  
2. Kräfte und Momente definiert  
3. Gleichungen ΣF = 0 und ΣM = 0 lösen  
4. Auflager- und Schnittkräfte berechnen  
5. Belastbarkeit und Stabilität prüfen  

## Kombinierbarkeit  
- Baustrukturen  
- Träger und Brücken  
- Roboterarme  
- Maschinenrahmen  
- Hydraulikzylinderbefestigungen  
- Hebezeuge und Kräne  

## Beispiele  
- Balken unter Last  
- Dreigelenkbogen  
- Wandkonsole  
- Kragarm  
- Kranabstützungen  

## Visualisierung (textuell)  
Kräfte wirken → Gleichgewichtsbedingungen → Auflagerkräfte entstehen → System bleibt stabil.

## Vorteile  
- einfache Gleichungen  
- universell anwendbar  
- direkte Verbindung zur Festigkeitslehre  

## Nachteile  
- gilt nur für ruhende oder quasistatische Systeme  
- dynamische Lasten nicht berücksichtigt  

## Quellen  
- Statik: Beer/Johnston  
- Grundlagen der Technischen Mechanik  
- Maschinenbau Statik (Freiheitsgrade & Auflagerlehre)
