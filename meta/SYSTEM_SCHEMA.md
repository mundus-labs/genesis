# MUNDUS LAB — SYSTEM SCHEMA

Das System Schema definiert die grundlegenden strukturellen Bausteine von MUNDUS.  
Es beschreibt, wie Wissen aufgenommen, zerlegt, validiert, gespeichert, verknüpft und analysiert wird.  
Alle Elemente dieses Schemas folgen den globalen Kernregeln von MUNDUS.

---

# 1. Steinformat (MMF)

Ein Stein ist die kleinste technische Einheit im gesamten System.  
Jeder Stein enthält exakt **eine technische Aussage** und folgt strikt diesem Format:

- **title**  
- **type** (funktion, prinzip, mechanismus, input, output, constraint, dependency, combinability)  
- **summary**  
- **details** (optional)  
- **requirements**  
- **results**  
- **relations** (erlaubte Beziehungstypen)  
- **source**  
- **version**  

Steine sind atomar, kombinierbar und maschinenlesbar.

---

# 2. Kategorien (MMF-Typen)

Die MMF-Kategorien definieren die Art der technischen Aussage:

- **funktion** — Was soll erreicht werden?  
- **prinzip** — Auf welchem Naturgesetz / logischen Zusammenhang basiert es?  
- **mechanismus** — Wie wird es umgesetzt?  
- **input** — Welche Zustände / Energie / Materialien sind notwendig?  
- **output** — Welche Zustände entstehen?  
- **constraint** — Welche Grenzen gelten?  
- **dependency** — Welche Faktoren müssen erfüllt sein?  
- **combinability** — Wie und womit ist der Stein kombinierbar?

Andere Kategorien sind im Kernsystem nicht erlaubt.

---

# 3. Wissensgraph (Knowledge Graph)

Der Graph speichert ausschließlich **validierte Steine** und ihre Beziehungen.  
Er ist die zentrale Struktur des Systems.

Er enthält:
- Steine (Knoten)  
- Beziehungen (gerichtete Kanten)  
- Cluster  
- Funktionsketten  
- Alternativen  
- Varianten  
- technische Zusammenhänge  

Erlaubte Beziehungstypen:

- **nutzt**  
- **basiert_auf**  
- **teil_von**  
- **alternative_zu**  
- **erweitert**  
- **ersetzt**  
- **verlangt**  
- **erzeugt**

Andere Beziehungstypen (z. B. "funktioniert mit", "benötigt", "widerspricht") sind **verboten**  
und würden das System inkonsistent machen.

---

# 4. Datenfluss-Schichten (Data Flow Layers)

### 4.1 Input Layer
Nimmt rohe technische Inhalte auf:
- Patente  
- Forschungspapiere  
- technische Dokumentationen  
- Zeichnungen / Diagramme  
- historische Mechanismen  

### 4.2 Parsing Layer
Strukturiert und segmentiert den Text:
- OCR  
- Segmentierung  
- technische Aussageerkennung  
- Chunking  

### 4.3 Decomposition Layer
Erzeugt **Roh-Steine** mit:
- vermutetem Typ  
- preliminary summary  
- vorläufigen Beziehungen  
- Quellen  

### 4.4 Validation Layer
Nutzer korrigiert:
- Typ  
- summary  
- requirements/results  
- Beziehungen  
- Quelle  

→ Ergebnis: **Stein Version 1.0.0**, gültig.

### 4.5 Graph Layer
Validierte Steine + Beziehungen werden gespeichert.  
Graph bildet technische Strukturen ab.

### 4.6 Sandbox Layer
Analysiert:
- Kompatibilität  
- Konflikte  
- Alternativen  
- Lücken  
- Optimierungslogik  

Erzeugt **keine neuen Steine**.

### 4.7 HRM Layer
Lernt aus:
- Korrekturen  
- Entscheidungen  
- Pfadnutzung  
- Kombinationen  

Beeinflusst:
- Vorschlagsranking  
- Zerlegungsschärfe  
- Relevanzlogik

---

# 5. KI-Schichten (konform & erlaubt)

### 5.1 Relevance Engine (statt „Semantic Module Retriever“)
Bestimmt relevante Steine basierend auf:
- Graphzentralität  
- HRM-Gewichtung  
- struktureller Nähe  

### 5.2 Compatibility Engine (statt „Constraint Engine“)
Prüft:
- technische Vereinbarkeit  
- gültige Input/Output-Ketten  
- Constraints  
- Dependencies  

### 5.3 Path Analyzer (statt „Design Generator“)
Analysiert mögliche Funktionspfade und Alternativen.  
Wichtig:  
**keine autonome Designgenerierung, keine neuen Steine** → nur Analyse.

### 5.4 HRM – Human Reward Model
Lernt Muster aus menschlicher Interaktion:
- Annahmen  
- Ablehnungen  
- Korrekturen  
- Ketten  
- Navigationsverhalten  

Steuert Prioritäten, niemals Inhalte.

---

# 6. Output Layer

Erzeugt:
- validierte Steine  
- Graphstrukturen  
- Funktionsketten  
- Systemanalysen  
- Vergleiche  
- Optimierungsvorschläge  
- visuelle Graphen  
- Systemberichte  

Kein autonomes „neue Erfindungen generieren“.  
Die Nutzer kombinieren — Sandbox analysiert.

---

# TL;DR

**Rohwissen → Parsing → Roh-Steine → Validierung → Graph → Sandbox → HRM → Analyse & technische Klarheit**

Nicht: „neue Erfindungen durch KI“  
sondern:  
**Menschen erfinden, MUNDUS strukturiert.**

