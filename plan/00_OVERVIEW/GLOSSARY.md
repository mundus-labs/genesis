# MUNDUS LAB — Glossar zentraler Begriffe

Dieses Glossar definiert alle Kernbegriffe, die in MUNDUS LAB genutzt werden.
Alle anderen Dokumente im Repository beziehen sich exakt auf diese Bedeutungen.
Begriffe dürfen nicht abgewandelt oder neu interpretiert werden.

---

## 1. Stein (Knowledge Stone)
Eine atomare, klar abgegrenzte Einheit technischen Wissens.
Ein Stein enthält genau **eine** Information, z. B. eine Funktion, ein Prinzip
oder einen Mechanismus. Steine sind kombinierbar, versionierbar und bilden die
Grundstruktur von MUNDUS.

---

## 2. MMF (Modular Modular Format)
Das standardisierte Format, in dem Steine gespeichert werden. Jeder Stein
folgt festen Kategorien wie Funktion, Prinzip, Mechanismus, Inputs, Outputs,
Constraints usw. Das MMF ist die „Sprache“ des Systems.

---

## 3. Roh-Stein (Raw Stone)
Ein automatisch aus Text oder Patent erzeugter Stein. Roh-Steine enthalten
Fehler und ungenaue Einordnungen. Sie werden vom Nutzer verfeinert.

---

## 4. Validierter Stein (Validated Stone)
Ein durch Nutzer korrigierter Stein. Er ist präziser, klar zugeordnet und
logisch verknüpfbar. Validierte Steine bilden den Kern des Wissensgraphen.

---

## 5. Wissensgraph (Knowledge Graph)
Die strukturierte, vernetzte Darstellung aller Steine und ihrer Beziehungen.
Zeigt, wie technische Elemente zusammenhängen und welche Alternativen existieren.

---

## 6. Beziehung (Relation)
Eine Verbindung zwischen Steinen, z. B.:
- „nutzt“
- „ersetzt“
- „entwickelt weiter“
- „teil von“
- „basiert auf“
Beziehungen werden im Graph gespeichert.

---

## 7. Werkstatt (Workshop)
Die Nutzeroberfläche, in der Steine:
- untersucht,
- verglichen,
- kombiniert,
- analysiert
werden können. Die Werkstatt ist der praktische Arbeitsbereich von MUNDUS.

---

## 8. Sandbox
Das logische Ausführungssystem, das Steine kombiniert, Regeln anwendet und
technische Vorschläge erzeugt. Keine vollphysikalische Simulation, sondern
modulare Logik.

---

## 9. HRM (Human Reward Model)
Ein Lernsystem, das aus tatsächlicher Nutzerinteraktion lernt. Es korrigiert die
automatische Zerlegung, verbessert Vorschläge der Sandbox und passt das System
an menschliche Präferenzen an.

---

## 10. Zerlegung (Decomposition)
Der Prozess, bei dem komplexe technische Texte (z. B. Patente) in Roh-Steine
aufgeteilt werden.

---

## 11. Patent-Stein
Ein Stein, der aus einem Patent stammt. Muss immer eindeutig einer MMF-Kategorie
zugeordnet werden (Funktion, Prinzip, Mechanismus usw.).

---

## 12. Nutzerkorrektur (User Refinement)
Der Vorgang, bei dem ein Nutzer einen Roh-Stein verbessert, neu einordnet oder
erweitert. Nutzer wirken intrinsisch, weil sie präzise Ergebnisse benötigen.

---

## 13. Kombination (Combination)
Das Verwenden mehrerer Steine zur Erzeugung oder Analyse eines technischen
Systems. Kombinationen können manuell (Werkstatt) oder vorgeschlagen (Sandbox)
entstehen.

---

## 14. Modul (Module)
Ein spezieller Stein oder eine Gruppe von Steinen aus dem `concepts/`-Ordner,
die allgemeines technisches Basiswissen repräsentieren (z. B. Mechanik,
Elektronik, Materialien).

---

## 15. Graph-Knoten (Node)
Jeder Stein im Wissensgraph ist ein Knoten. Beziehungen zwischen Knoten erzeugen
die Struktur des technischen Wissens.

---

## 16. Constraint
Eine Einschränkung oder Bedingung, die bei einem Stein berücksichtigt werden
muss (z. B. Materialgrenze, Temperaturbereich, Sicherheitsanforderung).

---

## 17. Input / Output
Eingangs- bzw. Ausgangsgrößen eines Steins. Beispiele:
- Input: Strom, Material, Kraft
- Output: Drehmoment, Wärme, Signal

---

## 18. Alternative Steinpfade (Alternative Paths)
Möglichkeiten, ein technisches Problem mit unterschiedlichen Steinen zu lösen.
Wird im Graph sichtbar.

---

## 19. Nutzerfluss (User Flow)
Die Abfolge von Aktionen, die ein Nutzer durchläuft: Hochladen → Zerlegung →
Korrektur → Werkstatt → Kombination → Ergebnis.

---

## 20. Lebensfunken (Minimum Viable Mundus)
Der kleinste funktionsfähige Zustand von MUNDUS:
1. Patent hochladen  
2. Roh-Steine erzeugen  
3. Nutzer korrigiert  
4. Speichern  
5. In der Werkstatt anzeigen  
6. Kombinationen ermöglichen  

Dies ist die Minimaldefinition eines lebenden MUNDUS-Systems.

---

## 21. Erweiterung (Extension)
Neuer Funktionsumfang, der sich auf bestehende Steine, Graphstrukturen oder
Werkzeuge aufsetzt, ohne das Kernmodell zu verändern.

---

## 22. Kernmodell (Core Model)
Die unveränderliche Struktur aus:
- Steinen,
- Graph,
- Werkstatt,
- Sandbox,
- HRM.

Alles in MUNDUS basiert auf diesem Modell. Es darf nicht umgebaut werden.

---

## 23. Intrinsische Motivation
Der Nutzer arbeitet sorgfältig, nicht wegen Belohnungen, sondern weil er ein
korrektes Ergebnis braucht, das ihm persönlich weiterhilft.

---

## 24. Systemgrenzen (System Boundaries)
Die definierte Grenze des Projekts. Alles, was außerhalb liegt, ist explizit in
`NON_GOALS.md` beschrieben.

