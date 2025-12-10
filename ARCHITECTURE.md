# MUNDUS LAB — ARCHITECTURE

Die Architektur von MUNDUS definiert, wie Rohwissen aus Patenten, Papern und technischen Dokumenten in präzise, validierte Steine umgewandelt wird, wie diese in einem globalen Wissensgraph organisiert werden und wie Sandbox und HRM technische Analyse und Lernprozesse unterstützen.

Die Systemarchitektur besteht aus sieben klar getrennten Schichten:

1. **Input Layer** — Wissen aufnehmen  
2. **Parsing Layer** — Texte vorstrukturieren  
3. **Decomposition Layer** — Roh-Steine erzeugen  
4. **Validation Layer** — Steine korrekt aufbereiten  
5. **Knowledge Graph Layer** — Wissen vernetzen  
6. **Sandbox Layer** — Analyse & Kombination  
7. **HRM Layer** — Lernen aus Nutzersignalen  

Diese Schichten bilden eine vollständig deterministische Pipeline.

---

# 1. Input Layer

Quellen technischer Inhalte:
- Patente  
- Forschungspapiere  
- technische Dokumentationen  
- historische Mechanismen  
- Diagramme & Zeichnungen  

Werkzeuge:
- OCR  
- Dateianalyse  
- Segmentierung  

Ziel: Rohwissen erfassen — noch ohne Interpretation.

---

# 2. Parsing Layer

Der Parsing Layer strukturiert Dokumente in analysierbare Textfragmente.

Methoden:
- Abschnittserkennung  
- Claim-Extraktion  
- technische Satzanalyse  
- Chunking von Mechanismen, Prinzipien, Funktionen  

Ziel: Der Text wird in logische Einheiten zerlegt, aus denen Roh-Steine erzeugt werden können.

---

# 3. Decomposition Layer

Der Decomposition Layer erzeugt **Roh-Steine** im MUNDUS-MMF-Format.

Ein Roh-Stein enthält:
- title  
- type (vermutet)  
- summary  
- details (optional)  
- requirements  
- results  
- preliminary relations  
- source  
- version = `0.1.0`  

Ziel: Aus Rohtext werden maschinenlesbare, kleinste technische Aussagen.

**Wichtig:**  
Der Decomposition Layer erzeugt *niemals* validierte Steine und trifft *niemals* technische Entscheidungen.

---

# 4. Validation Layer

Hier korrigiert der Mensch:

- Typ (MMF)  
- summary und details  
- requirements  
- results  
- Beziehungen (nur erlaubte Typen)  
- Quelle  

Nach Validierung erhält der Stein:
- Version `1.0.0`  
- endgültigen Status  
- Freigabe für den Graph  

Ziel: Qualitätssicherung durch menschliche Präzision.

---

# 5. Knowledge Graph Layer

Der Wissensgraph speichert nur **validierte Steine** und zulässige Beziehungen.

Erlaubte Beziehungstypen:
- **nutzt**  
- **basiert_auf**  
- **teil_von**  
- **alternative_zu**  
- **erweitert**  
- **ersetzt**  
- **verlangt**  
- **erzeugt**

Graph enthält:
- Steine (Knoten)  
- Beziehungen (gerichtete Kanten)  
- Cluster  
- Funktionsketten  
- Alternativen  
- Mechanismuslandschaften  

Ziel: Eine präzise, weltweit kombinierbare technische Wissensstruktur.

---

# 6. Sandbox Layer

Die Sandbox ist eine **deterministische Analyseengine**.

Sie darf:
- Kompatibilität prüfen  
- Konflikte identifizieren  
- alternative Steine finden  
- Optimierungspotenzial analysieren  
- Funktionsketten hervorheben  
- Lücken erkennen  

Sie darf **nicht**:
- neue Steine erzeugen  
- Designs generieren  
- autonom Innovation schaffen  
- spekulative Bedeutungen ableiten  

Ziel: Nutzer beim Verstehen, Vergleichen und Kombinieren technischer Steine unterstützen.

---

# 7. HRM Layer (Human Reward Model)

HRM ist die lernende Schicht von MUNDUS.

Es verarbeitet:
- Korrekturen  
- Annahmen von Vorschlägen  
- Ablehnungen  
- typische Systembau-Pfade  
- Navigationsmuster  

HRM darf:
- Prioritäten anpassen  
- Relevanz gewichteten  
- Vorschlagslogik verfeinern  
- Zerlegungsregeln verbessern  

HRM darf niemals:
- Steine verändern  
- Beziehungen verändern  
- Wissen überschreiben  
- neue Regeln erfinden  

Ziel: Das System durch reale Nutzung kontinuierlich verbessern.

---

# Ziel der Architektur

Eine klare, überprüfbare, deterministische Pipeline, die:

- Wissen strukturiert  
- Technik verständlich macht  
- Nutzer beim Denken unterstützt  
- Innovation vorbereitet  
- Qualität garantiert  

MUNDUS ist kein generatives KI-System, sondern eine **Maschine für technische Klarheit**.

---

# TL;DR

**Rohwissen → Parsing → Roh-Steine → Validierung → Graph → Sandbox → HRM → technische Erkenntnis**

Nicht automatisch, nicht spekulativ —  
immer logisch, immer nachvollziehbar, immer unter menschlicher Kontrolle.

