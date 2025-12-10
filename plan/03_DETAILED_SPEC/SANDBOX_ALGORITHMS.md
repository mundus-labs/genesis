# MUNDUS LAB — Sandbox Algorithms

Dieses Dokument beschreibt die Algorithmen, Logikregeln und Entscheidungsprozesse der MUNDUS Sandbox.  
Die Sandbox ist die technische Engine, die Vorschläge, Varianten, Konfliktanalysen und Systemprüfungen erzeugt.  
Sie ist kein generatives Modell, sondern ein strikt regelbasiertes, graphbasiertes und HRM-erweitertes Analysesystem.

---

## 1. Grundprinzip der Sandbox

Die Sandbox:
- analysiert Wissen  
- kombiniert Steine  
- erkennt Konflikte  
- findet Alternativen  
- prüft Systeme  
- optimiert Konstruktionen  

Sie arbeitet auf Basis von:
- Steinformat  
- Graphbeziehungen  
- Logikregeln  
- HRM-Gewichtungen  

Kein Schritt ist spekulativ, jeder Vorschlag muss logisch ableitbar sein.

---

## 2. Algorithmische Hauptelemente

### 2.1 Kompatibilitätsprüfung
Prüft, ob zwei oder mehr Steine kombinierbar sind.

Regeln:
- Output von Stein A muss Input von Stein B erfüllen  
- Constraints dürfen nicht verletzt werden  
- Mechanismus muss funktional zu Prinzip passen  
- Dependency muss erfüllt sein  
- keine widersprüchlichen Bedingungen  

Ergebnis:
- gültig  
- ungültig + Fehlergrund  

### 2.2 Pfadgenerierung (Graph Pathing)
Ermittelt mögliche Funktionsketten anhand des Graphen.

Mechanismus:
- Tiefensuche (DFS) für mögliche Ketten  
- Breitensuche (BFS) für Alternativen  
- Gewichtung durch HRM-Relevanz  

Ergebnis:
- mögliche technische Pfade  
- alternative Pfade  
- fehlende Verbindungen  

### 2.3 Alternativenfinder (Alternative Resolver)
Findet Steine mit:
- gleichem Typ  
- ähnlicher Funktion  
- kompatiblen Beziehungen  

Regeln:
- alternative_zu Beziehungen priorisiert  
- erweitert / ersetzt berücksichtigt  
- HRM-Verwendungshäufigkeit gewichtet  

### 2.4 Konflikterkennung
Erkennt logische Widersprüche.

Typische Konflikte:
- Input fehlt  
- Constraint verletzt  
- Mechanismus und Prinzip widersprechen sich  
- Dependency nicht erfüllt  
- zyklische Logik  

Konfliktresultat:
- "Konflikt erkannt"  
- exakte Ursache  
- mögliche Lösungssteine  

### 2.5 Optimierungsalgorithmus
Findet effizientere Varianten eines Systems.

Optimierung nach:
- minimalen Constraints  
- geringsten Dependencies  
- kürzesten Funktionsketten  
- stabilsten Mechanismen  
- häufig bewährten Mustern (HRM)  

### 2.6 Lückenerkennung (Gap Detection)
Analysiert Konstruktionen und erkennt:
- fehlende Zwischenmechanismen  
- notwendige Inputs  
- unstimmige Outputs  
- nicht geschlossene Funktionsketten  

Ergebnis:
- Liste fehlender Steine  
- Vorschläge zur Ergänzung  

---

## 3. Vorschlagslogik

### 3.1 Grundregeln
Ein Vorschlag muss:
- logisch ableitbar  
- technisch korrekt  
- graphbasiert  
- konsistent mit HRM  
sein.

### 3.2 Ranking von Vorschlägen
Ranking basiert auf:
- HRM-Relevanzscore  
- Strukturpassung  
- Steinqualität  
- Nutzerhistorie  
- Graphzentralität  

### 3.3 Ausschlussregeln
Vorschläge werden verworfen, wenn:
- Constraint verletzt ist  
- Dependency fehlt  
- Vorschlag zyklisch wäre  
- Vorschlag nicht deterministisch wäre  

---

## 4. Systemprüfung (System Validator)

Prüft komplette Konstruktionen und erzeugt:

1. Kompatibilitätsmatrix  
2. Konfliktliste  
3. fehlende Steine  
4. alternative Pfade  
5. Optimierungsvorschläge  

Validierung geschieht in drei Schichten:

### Schicht 1: Lokale Prüfung
Jede Verbindung wird einzeln geprüft.

### Schicht 2: Globale Prüfung
Gesamtsystem wird als Graph betrachtet.

### Schicht 3: HRM-Reflexion
Gewohnheitsmuster der Nutzer werden einbezogen.

---

## 5. Datenquellen der Sandbox

Die Sandbox verwendet:

- Steine (vollständig validiert)  
- Graphbeziehungen  
- Relevanzmetriken  
- HRM-Gewichtungen  
- historische Konstruktionsdaten  
- typologische Muster  

Keine externen Daten, kein spekulatives Wissen.

---

## 6. Algorithmische Stabilitätsregeln

### 6.1 Keine autonome Generierung
Die Sandbox darf nicht:
- neue Steine erzeugen  
- Beziehungen erstellen  
- Systeme bauen  

Nur analysieren und vorschlagen.

### 6.2 Vollständige Deterministik
Gleiche Eingabe → gleiche Ausgabe.

### 6.3 Keine unklaren Entscheidungen
Jeder Vorschlag muss begründet sein.

### 6.4 Keine probabilistischen Systeme
Nur logische und graphbasierte Methoden.

---

## 7. HRM-Integration

HRM beeinflusst die Sandbox durch:

- Verstärkung bewährter Kombinationen  
- Abschwächung seltener oder abgelehnter Vorschläge  
- Priorisierung von Alternativen  
- Optimierung der Kettenlängen  
- Anpassung von Gewichtungen  

HRM darf Sandbox-Logik verbessern, aber nicht verändern.

---

## 8. Erweiterbarkeit der Sandbox

Erlaubte Erweiterungen:
- neue Optimierungsregeln  
- neue Konfliktmuster  
- neue Rankingalgorithmen  
- bessere Visualisierungslogik  

Nicht erlaubt:
- neue Beziehungstypen  
- neue Steinarten  
- nicht deterministische Prozesse  
- autonome Generiersysteme  

---

## 9. Zusammenfassung

Die Sandbox arbeitet strikt:

- graphbasiert  
- logikgesteuert  
- deterministisch  
- durch HRM verfeinert  
- komplett transparent  

Sie erzeugt:
- Vorschläge  
- Optimierungen  
- Konfliktanalysen  
- Varianten  

Sie verändert nie Wissen — sie hilft dem Nutzer, es zu verwenden.

