# MUNDUS LAB — System Overview

Dieses Dokument beschreibt die Gesamtstruktur von MUNDUS.  
Es zeigt, wie alle Hauptkomponenten zusammenarbeiten, wie Daten fließen und wie das System technisch aufgebaut ist.  
Es dient als Orientierung für Architektur, Implementierung und Erweiterung.

---

## 1. Grundidee des Systems

MUNDUS zerlegt technisches Wissen in Steine, verknüpft sie im Wissensgraph, verarbeitet sie in der Sandbox, verbessert sie durch HRM und macht sie nutzbar in der Werkstatt.

Das System funktioniert als Kreislauf:

1. Wissen kommt ins System  
2. wird zerlegt  
3. vom Nutzer verbessert  
4. in den Graph gespeichert  
5. in der Werkstatt genutzt  
6. von der Sandbox kombiniert  
7. vom HRM optimiert  
8. fließt zurück als verbessertes Wissen

Dieser Kreislauf ist das technische Lebensprinzip von MUNDUS.

---

## 2. Die fünf Kernmodule

### 2.1 Steine
Atomare Wissenseinheiten.  
Basis aller Datenstrukturen.

### 2.2 Wissensgraph
Netzwerk der Steine und ihrer Beziehungen.  
Zentrale Navigations- und Strukturkomponente.

### 2.3 Werkstatt
User Interface für:
- Analyse  
- Kombination  
- Exploration  
- Konstruktion  

### 2.4 Sandbox
Logik-Engine für:
- Vorschläge  
- Alternativen  
- Systemprüfungen  
- Optimierungen  

### 2.5 HRM
Lernmotor des Systems.  
Verbessert Zerlegung, Vorschläge und Graphstruktur.

Diese Komponenten bilden die unveränderbare Basisschicht von MUNDUS.

---

## 3. Datenflüsse (high-level)

### 3.1 Eingehende Daten
- Patente  
- technische Dokumente  
- Forschung  
- manuell eingegebene Steine  

→ werden zu Roh-Steinen zerlegt.

### 3.2 Verarbeitung
- Nutzer validiert oder korrigiert Steine  
- neue Beziehungen entstehen  
- HRM lernt Muster  

### 3.3 Speicherung
Alle validierten Steine werden in den Wissensgraph integriert.  
Dieser wächst organisch und strukturiert sich durch Nutzerinteraktionen.

### 3.4 Nutzung
In der Werkstatt werden Steine:
- verglichen  
- kombiniert  
- analysiert  
- in Systemen genutzt  

Die Sandbox unterstützt diese Schritte.

### 3.5 Rückfluss
Das HRM lernt:
- welche Kombinationen sinnvoll sind  
- welche Vorschläge falsch sind  
- welche Muster sich wiederholen  

→ zukünftige Zerlegungen und Vorschläge werden besser.

---

## 4. Systemebenen (Layer)

MUNDUS hat vier technische Ebenen:

### Ebene 1 – Wissensebene  
- Steine  
- MMF-Struktur  
- Quellen  
- Versionierung  

### Ebene 2 – Strukturebene  
- Wissensgraph  
- Beziehungen  
- Knoten/Kanten-Modelle  

### Ebene 3 – Verarbeitungsebene  
- Sandbox (Logik-Engine)  
- Zerlegungssystem  
- HRM (Lernsystem)  

### Ebene 4 – Anwendungsebene  
- Werkstatt  
- Suche  
- Navigation  
- Konstruktion  
- Visualisierung  

Alle Ebenen sind streng voneinander getrennt, aber miteinander verbunden.

---

## 5. Architekturprinzipien

1. **Modularität**  
Jedes Modul ist klar definiert und unabhängig erweiterbar.

2. **Transparenz**  
Jede Entscheidung des Systems muss erklärbar sein.

3. **Determinismus auf Wissensebene**  
Steine und Beziehungen müssen eindeutig sein.

4. **Nutzerzentrierung**  
Der Nutzer entscheidet, HRM lernt.

5. **Schrittweises Wachstum**  
Keine monolithischen Features; alles baut aufeinander auf.

6. **Keine Blackboxen**  
Alle Regeln müssen offen, sichtbar und nachvollziehbar sein.

7. **Graphfirst**  
Der Graph ist die Quelle der Wahrheit.

---

## 6. Minimale Systemversion (Minimum Viable Mundus)

Für ein funktionierendes Basissystem braucht MUNDUS nur:

1. Patent/Text hochladen  
2. automatische Roh-Stein-Erzeugung  
3. Nutzerkorrektur  
4. Speicherung im Graph  
5. Anzeige in der Werkstatt  
6. einfache Kombinationen  
7. Sandbox-Checks  
8. HRM-Lernen aus Interaktionen  

Das ist der erste funktionsfähige Zustand des Systems.

---

## 7. Erweiterbarkeit

MUNDUS kann erweitert werden durch:
- neue Steinarten (innerhalb MMF)  
- neue Werkstattwerkzeuge  
- verbesserte Sandbox-Regeln  
- HRM-Optimierungen  
- Graph-Visualisierungen  
- neue Zerlegungsalgorithmen  

Solange der Kern unverändert bleibt, ist das System unbegrenzt skalierbar.

---

## 8. Ziel des Systemaufbaus

Das Ziel der Architektur ist:
- klare Struktur  
- logisches Wachstum  
- technische Präzision  
- maximale Erweiterbarkeit  
- minimale Komplexität für Nutzer  
- maximale Klarheit für Entwickler  
- absolute Stabilität der Kernidee  

MUNDUS soll eine technische Wissensplattform sein,  
die durch Nutzung intelligenter wird und nie überladen wirkt.

