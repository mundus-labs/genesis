# MUNDUS LAB — DATA FLOW

Dieses Dokument beschreibt den vollständigen Datenfluss innerhalb von MUNDUS.  
Er zeigt, wie aus unstrukturiertem Rohwissen validierte Steine, Wissensbeziehungen, technische Systeme und analysierbare Konstruktionen entstehen.

Der Datenfluss folgt streng der Reihenfolge:
**Input → Parsing → Zerlegung → Validierung → Graph → Sandbox → HRM → Output**

---

## 1. Input Layer — Rohdaten

Quellen für technische Inhalte:
- Patente  
- Forschungspapiere  
- technische Dokumentationen  
- historische Mechanismen  
- Zeichnungen & Diagramme  
- Laborberichte  

Ziel: Möglichst viel technisches Wissen in unverarbeiteter Form erfassen.  
(Hinweis: *Rohdaten werden nie direkt in den Graph übernommen.*)

---

## 2. Parsing Layer — Vorstrukturierung des Textes

Funktionen:
- OCR (falls Dokumente gescannt sind)  
- Segmentierung in Abschnitte  
- Extraktion technischer Aussagen  
- Erkennung von Bauteilen, Prinzipien, Mechanismen  
- Chunking in logisch getrennte Textblöcke  

Ziel: Rohtext in analysierbare Einheiten zerlegen, die für die Zerlegung vorbereitet sind.  
(Hinweis: *Dies erzeugt noch keine Steine.*)

---

## 3. Decomposition Layer — Roh-Steine erzeugen

Für jedes identifizierte technische Fragment wird ein **Roh-Stein** erstellt mit:
- vermuteter Kategorie (funktion, prinzip, mechanismus, input, output, constraint, dependency, combinability)  
- vorläufiger Zusammenfassung  
- rudimentären Beziehungen  
- Quellenangabe  
- Version: `0.1.0`  

Ziel: Sämtliches Wissen in atomare technische Aussagen aufteilen.  
(Hinweis: *Roh-Steine sind NIE graphfähig.*)

---

## 4. Validation Layer — Steinvalidierung

Nutzer korrigiert:
- Kategorie  
- summary  
- details  
- requirements  
- results  
- Beziehungen (nur gültige Typen: nutzt, basiert_auf, teil_von, alternative_zu, erweitert, ersetzt, verlangt, erzeugt)  
- Quelle  

Nach Abschluss erhält der Stein:
- Version `1.0.0`  
- Status „validiert“  

Ziel: Aus Roh-Steinen werden gültige Steine.

---

## 5. Graph Layer — Wissen strukturieren

Der Wissensgraph speichert:
- alle validierten Steine  
- alle gültigen Beziehungen  
- thematische Cluster  
- Funktionsketten  
- alternative Mechanismen  
- Hierarchien technischer Systeme  

Erlaubte Beziehungen:
- nutzt  
- basiert_auf  
- teil_von  
- alternative_zu  
- erweitert  
- ersetzt  
- verlangt  
- erzeugt  

Ziel: Ein globaler, sauber definierter technischer Wissensgraph.

---

## 6. Sandbox Layer — Analyse & Kombination

Sandbox verwendet NUR validierte Steine.

Funktionen:
- Kompatibilität prüfen  
- Konflikte erkennen  
- alternative Mechanismen vorschlagen  
- Lücken identifizieren  
- funktionale Pfade analysieren  
- einfache Optimierungen berechnen  

Ziel: Nutzer beim Kombinieren, Analysieren und Verbessern technischer Systeme unterstützen.  
(Hinweis: *Sandbox erzeugt keine neuen Steine.*)

---

## 7. HRM Layer — Lernen aus Nutzersignalen

HRM erhält:
- Korrektursignale  
- Annahme-/Ablehnungssignale  
- Systembau-Muster  
- Navigationspfade  

HRM beeinflusst:
- Priorisierung von Vorschlägen  
- Qualität der Zerlegung  
- Relevanz von Alternativen  
- Gewichtung technischer Pfade  

Ziel: Die Qualität des Systems durch echtes menschliches Verhalten verbessern.  
(Hinweis: *HRM ändert nie Wissen, nur Gewichtungen.*)

---

## 8. Output Layer — Nutzbare Ergebnisse

Aus dem gesamten Pipeline-Prozess entstehen:

- validierte Steine  
- graphbare Wissensstrukturen  
- Systemmodelle  
- Sandbox-Analysen  
- technische Vergleiche  
- Optimierungsvorschläge  
- vollständige Funktionsketten  
- visuelle Graphdarstellungen  

Ziel: Aus Rohwissen werden nutzbare technische Strukturen, mit denen Menschen arbeiten, vergleichen, erfinden und optimieren können.

---

## TL;DR

**Rohwissen rein → Parsing → Roh-Steine → Validierung → Wissensgraph → Sandbox → HRM → Klarheit & neue technische Möglichkeiten raus.**

