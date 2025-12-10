# MUNDUS LAB — System Interactions

Dieses Dokument beschreibt alle Interaktionen innerhalb des MUNDUS-Systems:
- zwischen Nutzer und Komponenten,
- zwischen Komponenten untereinander,
- zwischen Verarbeitungsschichten und dem Wissensgraph.

Interaktionen definieren, wie das System funktioniert, reagiert und lernt.

---

## 1. Nutzerinteraktionen

Der Nutzer interagiert direkt mit den sichtbaren Teilen des Systems.  
Alle Aktionen des Nutzers erzeugen Signale für HRM und wirken sich auf den Graphen aus.

### 1.1 Steine ansehen
- Nutzer öffnet Steinansicht  
- System zeigt Inhalte, Beziehungen, Versionen  
- HRM registriert Relevanz  

### 1.2 Steine vergleichen
- Nutzer wählt mehrere Steine  
- Werkstatt zeigt Unterschiede, Gemeinsamkeiten, Alternativen  
- Sandbox liefert mögliche Kombinationen  

### 1.3 Steine korrigieren
- Nutzer korrigiert Typ, Inhalt, Beziehungen  
- HRM verarbeitet Korrektursignal  
- Graph aktualisiert Knoten und Kanten  

### 1.4 Steine kombinieren
- Nutzer verbindet Steine zu Systemen  
- Sandbox prüft Kompatibilität  
- Werkstatt visualisiert System  

### 1.5 Systeme analysieren
- Nutzer wählt System  
- Sandbox prüft:
  - fehlende Inputs  
  - Constraint-Verletzungen  
  - alternative Mechanismen  

### 1.6 Systeme konstruieren
- Nutzer baut Systeme aus Steinen  
- Sandbox liefert Vorschläge  
- HRM lernt Muster  

### 1.7 Vorschläge annehmen oder ablehnen
- Angenommen → Stärkt Vorschlagslogik  
- Abgelehnt → Korrigiert Vorschlagslogik  
- Neutral → Keine Änderung  

### 1.8 neue Steine erstellen
- Nutzer erzeugt fehlende Wissenseinheiten  
- Graph erweitert sich  
- HRM registriert Bedarfsmuster  

---

## 2. Sandbox-Interaktionen

Die Sandbox interagiert mit:

### 2.1 Werkstatt
Werkstatt → Sandbox:
- aktuelle Konstruktionen  
- selektierte Steine  
- Analysefragen  

Sandbox → Werkstatt:
- Vorschläge  
- Alternativen  
- Konfliktwarnungen  
- fehlende Steine  

### 2.2 Graph
Sandbox liest:
- Beziehungen  
- Knotenstrukturen  
- Stein-Typen  
- Cluster  

Sandbox schreibt:
- Relevanzwerte  
- Optimierungskandidaten  

### 2.3 HRM
Sandbox erhält Signale für:
- Bewertung der Vorschläge  
- Verbesserung der Logik  
- Anpassung zukünftiger Empfehlungen  

---

## 3. HRM-Interaktionen

HRM ist das lernende System, das Feedback aus allen Interaktionen verarbeitet.

### 3.1 HRM liest aus:
- Korrekturen  
- Annahmen/Ablehnungen  
- Navigationspfaden  
- Konstruktionen  
- Graphänderungen  

### 3.2 HRM schreibt in:
- Zerlegungsregeln  
- Priorisierung von Beziehungen  
- Sandbox-Lernparameter  
- Gewichtung von Alternativen  

---

## 4. Graph-Interaktionen

Der Graph steht im Zentrum der Systemstruktur.

### 4.1 Nutzer ↔ Graph
- Nutzer navigiert  
- Nutzer modifiziert Beziehungen  
- Graph zeigt Alternativen  

### 4.2 Sandbox ↔ Graph
- Sandbox nutzt Graph zur Logikbildung  
- Sandbox ergänzt Relevanzwerte  

### 4.3 HRM ↔ Graph
- HRM stärkt häufige Muster  
- HRM schwächt falsche Muster  

### 4.4 Zerlegung ↔ Graph
- neue Roh-Steine generieren neue Knoten  
- Beziehungen werden vorgeschlagen  

---

## 5. Interaktionen zwischen Systemschichten

### 5.1 Wissensebene → Strukturebene
Steine werden in den Graph übertragen.

### 5.2 Strukturebene → Verarbeitungsebene
Der Graph liefert:
- Pfade  
- Alternativen  
- Kontext  
- Kompatibilität  

### 5.3 Verarbeitungsebene → Anwendungsebene
Sandbox liefert Werkstatt:
- Vorschläge  
- Alternativen  
- Warnungen  

### 5.4 Anwendungsebene → Lernschicht
Werkstatt liefert HRM:
- Korrekturen  
- Entscheidungen  
- Pfade  
- Kombinationen  

### 5.5 Lernschicht → Wissensebene
HRM verbessert:
- Zerlegung  
- Klassifizierung  
- Beziehungen  

---

## 6. Systemverhalten (Interaktionsprinzipien)

1. Der Nutzer entscheidet, das System folgt.  
2. Kein Autoverhalten ohne Nutzerinput.  
3. Jede Interaktion erzeugt strukturierbares Wissen.  
4. Das System ist deterministisch auf Wissensebene.  
5. Vorschläge müssen erklärbar sein.  
6. Keine Hidden States.  
7. Jede Änderung ist rückverfolgbar.  
8. Das System lernt nur aus echten Interaktionen.  

---

## 7. Zusammenfassung

Die Interaktionen von MUNDUS bilden ein geschlossenes System:

- Nutzer interagiert  
- Sandbox analysiert  
- Graph strukturiert  
- HRM lernt  
- Zerlegung wird besser  
- Wissen wächst  
- Nutzer erhält bessere Werkzeuge  

Interaktionen sind der Mechanismus, durch den MUNDUS lebendig und wachsend wird.

