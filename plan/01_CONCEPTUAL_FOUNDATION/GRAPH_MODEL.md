# MUNDUS LAB — Wissensgraph (Graph Model)

Der Wissensgraph ist die strukturelle Basis von MUNDUS.  
Er verbindet alle Steine logisch miteinander und macht sichtbar,  
wie technische Prinzipien, Funktionen und Mechanismen zusammenhängen.

Der Graph ist kein optionales Modul – er ist das Nervensystem des gesamten Projekts.

---

## 1. Zweck des Graphen

Der Graph dient dazu:
- Steine zu verknüpfen,
- technische Zusammenhänge abzubilden,
- Alternativen sichtbar zu machen,
- Kombinationen möglich zu machen,
- die Sandbox mit Struktur zu versorgen,
- Nutzer durch das Wissen zu navigieren.

Der Graph macht Technik als Netzwerk darstellbar.

---

## 2. Grundaufbau

Der Wissensgraph besteht aus:
- **Knoten** → einzelne Steine  
- **Kanten** → Beziehungen zwischen Steinen  

Jeder Stein ist ein Knoten.  
Jede Beziehung ist eine gerichtete oder ungerichtete Kante.

---

## 3. Knotentypen

Alle Knoten sind Steine, d. h. Instanzen einer MMF-Kategorie:

- Funktion  
- Prinzip  
- Mechanismus  
- Input  
- Output  
- Constraint  
- Dependency  
- Combinability  

Mehr Knotentypen dürfen niemals eingeführt werden.

---

## 4. Beziehungstypen (Kanten)

Beziehungen beschreiben den technischen Zusammenhang zwischen zwei Steinen.

Zulässige Beziehungstypen sind:

- **nutzt**  
- **basiert_auf**  
- **teil_von**  
- **alternative_zu**  
- **ersetzt**  
- **erweitert**  
- **verlangt** (erfordert Input/Dependency)  
- **erzeugt** (von Mechanismus zu Output)  

Jede Beziehung muss logisch und technisch nachvollziehbar sein.

---

## 5. Regeln für Beziehungen

1. Beziehungen müssen klar begründet sein.  
2. Beziehungen dürfen niemals widersprüchlich sein.  
3. Beziehungen müssen konsistent mit Stein-Typen sein.  
4. Beziehungen dürfen nicht spekulativ sein.  
5. Beziehungen dürfen nur technische Logik abbilden.  
6. Beziehungen müssen minimal sein – kein unnötiger Graphmüll.  
7. Nutzer müssen Beziehungen korrigieren können.  

---

## 6. Wie Beziehungen entstehen

### 6.1 Automatisch (erste Version)
Bei der Zerlegung werden Vorschlagsbeziehungen generiert:
- Mechanismus nutzt Prinzip  
- Funktion basiert auf Mechanismus  
- Mechanismus erzeugt Output  
- Constraint begrenzt Mechanismus  

Diese Roh-Beziehungen können falsch oder unvollständig sein.

### 6.2 Durch Nutzerkorrektur
Nutzer können:
- falsche Kanten löschen,
- fehlende Kanten hinzufügen,
- Typen korrigieren,
- Beziehungen neu strukturieren.

### 6.3 Durch HRM-Lernen
HRM erkennt Muster:
- häufig vorkommende Steinpaare,
- gültige Funktionsketten,
- typische Alternativen,
- häufig korrigierte Fehler.

Es verbessert zukünftige Vorschläge.

---

## 7. Graph-Operationen in MUNDUS

Der Graph ermöglicht:

### 7.1 Navigation
- von Stein zu Stein springen  
- technische Landschaften erkunden  

### 7.2 Clustering
- thematische Gruppen von Steinen erkennen  
- Mechanismusfamilien identifizieren  
- Prinzipiengruppen sichtbar machen  

### 7.3 Pfadanalyse
- Funktionsketten  
- Prozessketten  
- Energieflussketten  

### 7.4 Alternativenanalyse
- alternative Mechanismen  
- alternative Prinzipien  
- alternative Funktionswege  

### 7.5 Vollständigkeitsanalyse
- fehlende Inputs  
- fehlende Mechanismen  
- Lücken im System  

### 7.6 Konfliktanalyse
- widersprüchliche Steine  
- Constraint-Verletzungen  
- unpassende Kombinationen  

Der Graph ist das Werkzeug zur Erkenntnis.

---

## 8. Verbindung zu anderen Modulen

### 8.1 Werkstatt
Die Werkstatt nutzt den Graphen für:
- visuelle Darstellung  
- Vergleich  
- Kombination  
- Analyse  

### 8.2 Sandbox
Die Sandbox nutzt den Graphen für:
- Vorschläge  
- Alternativen  
- Optimierungen  
- Fehlersuche  

### 8.3 HRM
HRM nutzt Graphdaten als Lernmaterial.

### 8.4 Steine
Steine sind der Inhalt des Graphen.

---

## 9. Wachstum des Graphen

Der Graph wächst durch:
- neue Steine  
- neue Beziehungen  
- Nutzerkorrektur  
- HRM-Lernen  
- neue technische Quellen  

Je größer der Graph, desto intelligenter wird das gesamte System.

---

## 10. Ziel des Graphen

Der Wissensgraph soll die technische Welt so darstellen,  
dass sie:
- verständlich,  
- strukturiert,  
- navigierbar,  
- kombinierbar,  
- erweiterbar  

wird.

Er bildet die Grundlage für Analyse, Kreativität und Innovation in MUNDUS.

