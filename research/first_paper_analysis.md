# MUNDUS LAB — First Paper Analysis (Template)

Diese Datei dient als Vorlage für die Analyse eines Patents, Papers oder technischen Dokuments.  
Ziel ist es, technische Inhalte in **Roh-Steine** zu zerlegen, gültige Beziehungen abzuleiten und neues Wissen in MUNDUS einzuspeisen.

---

## 1. Quelle

Titel:  
Autor(en):  
Jahr:  
Typ: Patent / Paper / Bericht / Manual  
Patentnummer / DOI / Link:  

Kurzbeschreibung der Quelle:

---

## 2. Identifikation technischer Aussagen

Liste zentraler technischer Aussagen, Mechanismen, Prinzipien oder Abhängigkeiten:

-  
-  
-  

Diese Aussagen werden im nächsten Schritt in **Roh-Steine** überführt.

---

## 3. Zerlegung in Roh-Steine (MMF-konform)

Für jede identifizierte Aussage entsteht ein Roh-Stein im MUNDUS-MMF-Format:

**Roh-Stein (Template):**  
- **title:**  
- **type (vermutet):** funktion / prinzip / mechanismus / input / output / constraint / dependency / combinability  
- **summary:**  
- **details:**  
- **requirements:**  
- **results:**  
- **relations (vorläufig):**  
- **source:**  
- **version:** 0.1.0  

Neue Roh-Steine aus dieser Analyse:

- stein_001:  
- stein_002:  
- stein_003:  

Hinweis:  
Diese Steine müssen im Validierungsprozess **manuell korrigiert und bestätigt** werden.

---

## 4. Beziehungen (Graph)

Erlaubte Beziehungstypen:

- **nutzt**  
- **basiert_auf**  
- **teil_von**  
- **alternative_zu**  
- **erweitert**  
- **ersetzt**  
- **verlangt**  
- **erzeugt**

Vorläufige Graph-Beziehungen aus dieser Analyse:

- stein_001 basiert_auf stein_002  
- stein_003 teil_von stein_001  
- stein_002 verlangt stein_004  
- …

Diese Beziehungen werden erst gültig, wenn:
1. die Steine validiert wurden, und  
2. die Beziehungen logisch geprüft sind.

---

## 5. Erkenntnisse aus der Quelle

Kurze Zusammenfassung der wichtigsten technischen Erkenntnisse:

-  
-  
-  

---

## 6. Potenzielle technische Lücken / Ergänzungen

Die Analyse kann zeigen, dass im System bestimmte Steine fehlen:

- fehlender Mechanismus:  
- fehlendes Prinzip:  
- fehlende Funktion:  
- fehlende Abhängigkeit:  

Diese Lücken sind Hinweise für neue Steine oder Ergänzungen.

---

## 7. Mögliche Kombinationen (Analyse, keine Generierung)

Die Sandbox darf nur analysieren, niemals erzeugen.

Mögliche Kombinationen zur späteren Werkstattprüfung:

-  
-  
-  

---

## 8. Offene Fragen / Weiterführende Arbeit

- Welche Steine müssen präziser werden?  
- Welche Beziehungen sind unsicher?  
- Welche Aussagen müssen weiter zerlegt werden?  
- Benötigen wir zusätzliche Quellen?  

---

## TL;DR

Quelle lesen → technische Aussagen extrahieren → Roh-Steine erzeugen →  
vorläufige Beziehungen ableiten → Lücken erkennen → Validierung →  
Integration in den Wissensgraph.
