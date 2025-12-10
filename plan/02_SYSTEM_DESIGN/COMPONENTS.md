# MUNDUS LAB — System Components

Dieses Dokument beschreibt alle Hauptkomponenten des MUNDUS-Systems.  
Jede Komponente hat eine klar definierte Rolle und ist mit den anderen
über feste Schnittstellen verbunden.  
Die Komponenten zusammen ergeben ein modulares, skalierbares und lernfähiges
technisches Wissenssystem.

---

## 1. Knowledge Components (Wissen)

### 1.1 Steine (Knowledge Stones)
Atomare Wissenseinheiten.  
Sie bilden die Grundlage des gesamten Systems.

Enthalten:
- eine technische Aussage  
- Kategorie (MMF)  
- Inputs, Outputs, Constraints  
- Beziehungen  
- Quelle  
- Version  

### 1.2 Wissensgraph (Knowledge Graph)
Netzwerk aller Steine und Beziehungen.

Funktionen:
- Navigation  
- Analyse  
- Ähnlichkeitserkennung  
- Alternativensuche  
- Funktionsketten darstellen  

### 1.3 Beziehungen (Relations)
Verbinden Steine über definierte Logiktypen:
- nutzt  
- basiert_auf  
- teil_von  
- alternative_zu  
- erweitert  
- ersetzt  
- verlangt  
- erzeugt  

---

## 2. Processing Components (Verarbeitung)

### 2.1 Zerlegungssystem (Decomposition Engine)
Erzeugt Roh-Steine aus:
- Patenten  
- technischen Texten  
- Dokumenten  
- Standards  
- Nutzerinhalten  

Lieferprodukte:
- Roh-Steine  
- vorläufige Kategorien  
- erste Beziehungen  

### 2.2 Sandbox (Reasoning Engine)
Analysiert Wissen und erzeugt:
- Kombinationsvorschläge  
- Alternativen  
- Konflikterkennung  
- Optimierungen  
- Systempfade  

Verwendet:
- Logikregeln  
- Graphbeziehungen  
- HRM-Signale  

### 2.3 HRM (Human Reward Model)
Lernt aus Nutzerinteraktionen.

Verbessert:
- Zerlegung  
- Vorschlagslogik  
- Beziehungen  
- Relevanz von Steinen  

Wesentliche Signalarten:
- Korrektur  
- Annahme  
- Ablehnung  
- Kombination  
- Navigation  
- Konstruktion  

---

## 3. Application Components (Nutzerinteraktion)

### 3.1 Werkstatt (Workshop)
Zentrale Nutzeroberfläche.

Bietet:
- Einzelsteinansicht  
- Vergleich  
- Kombination  
- Analyse  
- Exploration  
- Systembau  

### 3.2 Navigation & Suche
Schnittstellen zum Erkunden des Wissensgraphen:
- Suche nach Steinen  
- Navigation entlang der Kanten  
- Cluster-Ansicht  
- thematische Pfade  

### 3.3 Systemkonstruktion
Werkzeuge zum:
- Zusammenbauen  
- Zerlegen  
- Optimieren  
- Vergleichen  
- Transformieren  

der technischen Systeme.

---

## 4. Storage Components (Speicherung)

### 4.1 Stein-Datenbank
Speichert:
- Inhalt  
- Typ  
- Version  
- Quelle  
- zugehörige Beziehungen  

### 4.2 Graph-Datenbank
Speichert:
- Knoten (Steine)  
- Kanten (Beziehungen)  
- Cluster  
- Relevanzen  
- Graphmetriken  

### 4.3 HRM-Feedbackspeicher
Speichert:
- Korrekturereignisse  
- Annahmen/Ablehnungen  
- Nutzungsmuster  
- technische Pfade  

---

## 5. System Interfaces (Interne Schnittstellen)

### 5.1 Werkstatt ↔ Sandbox
Die Werkstatt liefert:
- aktuelle Konstruktionen  
- Kombinationen  
- Nutzerwünsche  

Die Sandbox liefert:
- Vorschläge  
- Varianten  
- Konfliktanalysen  
- fehlende Steine  

### 5.2 Sandbox ↔ Graph
Sandbox liest:
- Beziehungen  
- mögliche Pfade  
- kompatible Knoten  

Sandbox schreibt:
- Relevanzwerte  
- Beziehungsvorschläge  

### 5.3 HRM ↔ Zerlegung
HRM verbessert:
- Klassifikationsregeln  
- Zerlegungspfade  
- Priorisierungen  

### 5.4 Graph ↔ Werkstatt
Werkstatt nutzt:
- Graphstruktur  
- Alternativen  
- verwandte Mechanismen  

---

## 6. External Components (Optionale Erweiterungen)

- Export-Module  
- Visualisierungsmodule  
- API-Schichten  
- Kollaborationsfeatures  
- Simulationsbrücken (nur logikbasiert, keine Physiksimulation)

Diese Komponenten erweitern MUNDUS, verändern aber nie den Kern.

---

## 7. Zusammenfassung

Die MUNDUS-Komponenten bilden ein klares Modulsystem:

1. Wissen: Steine + Graph  
2. Verarbeitung: Zerlegung + Sandbox + HRM  
3. Anwendung: Werkstatt + Navigation + Konstruktion  
4. Speicherung: Stein-DB + Graph-DB + HRM-DB  

Jedes Modul erfüllt eine präzise Aufgabe.  
Gemeinsam bilden sie ein wachsendes, lernendes Wissensökosystem.

