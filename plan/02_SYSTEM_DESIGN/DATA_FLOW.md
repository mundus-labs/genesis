# MUNDUS LAB — Data Flow

Dieses Dokument beschreibt den vollständigen Datenfluss in MUNDUS – von der ersten Aufnahme technischer Informationen bis hin zur Nutzung, Verbesserung und Rückführung in das System.  
Der Data Flow zeigt, wie Wissen verarbeitet, gespeichert, kombiniert und durch Nutzerinteraktion verbessert wird.

Der gesamte Datenfluss ist zyklisch und selbstverstärkend.

---

## 1. Eingangsdaten

MUNDUS verarbeitet folgende Eingangsdaten:

- Patente  
- technische Dokumentationen  
- wissenschaftliche Artikel  
- Normen und Standards  
- manuell erzeugte Steine  
- Module aus dem `concepts/`-Ordner  

Diese Daten bilden die Grundlage des Systems.

---

## 2. Zerlegung (Decomposition)

Eingangsdaten werden automatisch analysiert und zerlegt in:

- Roh-Steine  
- vermutete Stein-Typen  
- grobe Beschreibungen  
- Kandidatenbeziehungen  

Ziel der Zerlegung:
Komplexe Texte in strukturiertes Wissen transformieren.

Roh-Steine sind bewusst ungenau und benötigen menschliche Verfeinerung.

---

## 3. Validierung (User Refinement)

Nutzer verbessern die Roh-Steine in der Werkstatt:

- Kategorisieren richtig  
- präzisieren Inhalte  
- ergänzen Constraints  
- definieren Inputs/Outputs  
- verbessern Zusammenhänge  
- löschen oder erzeugen Beziehungen  

Ergebnis:
Validierte Steine (machine-ready knowledge units).

---

## 4. Speicherung im Wissensgraph

Validierte Steine fließen in den Graph ein:

- jeder Stein = Knoten  
- jede Beziehung = Kante  
- der Graph wächst organisch  
- thematische Cluster entstehen  
- technische Pfade werden sichtbar  

Der Graph wird zur zentralen Wissensquelle.

---

## 5. Nutzung in der Werkstatt

Der Nutzer arbeitet direkt auf dem gespeicherten Wissen:

- Steine ansehen  
- Steine vergleichen  
- Steine kombinieren  
- Systeme konstruieren  
- Alternativen prüfen  
- Varianten ableiten  
- Mechanismen untersuchen  

Nutzerinteraktion erzeugt neue Datenpunkte für HRM.

---

## 6. Verarbeitung durch die Sandbox

Die Sandbox analysiert:

- Kompatibilität von Steinen  
- logische Ketten  
- alternative Mechanismen  
- Konflikte  
- Constraint-Verletzungen  
- fehlende Bausteine  
- Optimierungspotenzial  

Sie nutzt:
- Stein-Logik  
- Graphbeziehungen  
- HRM-Lernsignale  

Ergebnis:
Vorschläge, Varianten, Optimierungen.

---

## 7. HRM-Feedbackschicht

Jede Nutzeraktion liefert HRM-Signale:

- Korrekturen: verbessern Zerlegung  
- Ablehnungen: korrigieren Sandbox-Logik  
- Annahmen: verstärken gute Muster  
- Kombinationen: stärken technische Pfade  
- Navigation: zeigt relevante Zusammenhänge  
- Konstruktionen: bestätigen funktionale Strukturen  

Das HRM modelliert den menschlichen technischen Entscheidungsprozess.

---

## 8. Systemverbesserung

Das System verbessert sich kontinuierlich:

- Roh-Steine werden präziser  
- Beziehungen werden korrekter  
- Graphstrukturen werden dichter  
- Vorschläge werden relevanter  
- Zerlegungsregeln werden intelligenter  
- das gesamte Wissen wächst strukturiert  

Dies ist der selbstverstärkende Kern des Systems.

---

## 9. Kreislauf

Der Datenfluss ist zyklisch:

1. Daten kommen ins System  
2. werden zerlegt  
3. vom Nutzer korrigiert  
4. in den Graph integriert  
5. in der Werkstatt verwendet  
6. von der Sandbox analysiert  
7. vom Nutzer bewertet  
8. vom HRM gelernt  
9. System verbessert sich  
10. neuer Zyklus beginnt  

Der Data Flow ist der technische Blutkreislauf von MUNDUS.

---

## 10. Zusammenfassung

Der Datenfluss in MUNDUS ist:
- strukturiert  
- zyklisch  
- wachsend  
- nutzergetrieben  
- lernfähig  
- graph-basiert  
- modular  

Daten werden zu Wissen, Wissen wird zu Strukturen, Strukturen werden zu neuen technischen Möglichkeiten.  
Das System wird mit jeder Nutzung intelligenter.

