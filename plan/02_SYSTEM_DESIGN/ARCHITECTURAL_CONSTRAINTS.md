# MUNDUS LAB — Architectural Constraints

Dieses Dokument definiert die unveränderbaren architektonischen Beschränkungen von MUNDUS.  
Sie stellen sicher, dass das System über Jahre hinweg stabil, verständlich und erweiterbar bleibt.  
Alle zukünftigen Erweiterungen müssen diesen Regeln folgen.

---

## 1. Kernprinzipien (nicht verhandelbar)

### 1.1 Steine sind atomar
Ein Stein enthält genau **eine** technische Aussage.  
Keine Vermischungen, keine zusammengesetzten Konzepte.

### 1.2 Der Graph ist die Quelle der Wahrheit
Jedes Stück Wissen, jeder Zusammenhang, jede Struktur existiert im Wissensgraph.  
Keine parallelen Wissenssysteme.

### 1.3 Nutzerentscheidungen sind final
Das System darf nie autonom Entscheidungen treffen.  
Der Mensch korrigiert, bestätigt und steuert.

### 1.4 HRM lernt nur aus echter Nutzung
Keine künstlichen Trainingsdaten.  
Keine automatischen Optimierungsloops ohne Nutzer.

### 1.5 Sandbox agiert nie eigenständig
Keine automatischen Konstruktionen.  
Keine autonomen Lösungen.  
Nur Vorschläge — nie Entscheidungen.

---

## 2. Strukturelle Beschränkungen

### 2.1 Nur MMF-Kategorien
Erlaubte Stein-Typen:
- Funktion  
- Prinzip  
- Mechanismus  
- Input  
- Output  
- Constraint  
- Dependency  
- Combinability  

Neue Typen sind verboten.

### 2.2 Nur definierte Beziehungstypen
Erlaubte Kanten:
- nutzt  
- basiert_auf  
- teil_von  
- alternative_zu  
- erweitert  
- ersetzt  
- verlangt  
- erzeugt  

Keine freien oder undefinierten Beziehungstypen.

### 2.3 Keine verschachtelten Steinstrukturen
Steine sind flach strukturiert.  
Hierarchien existieren nur im Graph.

### 2.4 Graph ist immer konsistent
Beziehungen müssen:
- logisch  
- erklärbar  
- technisch gültig  
sein.

---

## 3. Verhaltensbeschränkungen

### 3.1 Keine Hidden States
Das System darf keine nicht nachvollziehbaren Zustände oder Entscheidungen erzeugen.

### 3.2 Jede Empfehlung muss begründet sein
Die Sandbox muss erklären können:
- warum ein Vorschlag gemacht wurde  
- auf welchen Steinen er basiert  
- welche Pfade genutzt wurden  

### 3.3 Kein Overruling des Nutzers
Nutzerentscheidungen dürfen niemals überschrieben werden.

### 3.4 Keine unkontrollierte Datenmanipulation
Jede Veränderung muss:
- sichtbar  
- nachvollziehbar  
- revertierbar  
sein.

---

## 4. Lernbeschränkungen (HRM)

### 4.1 HRM darf Nutzer nicht bewerten
Kein Ranking.  
Keine Punktzahl.  
Keine Nutzerbewertung.

### 4.2 HRM lernt nur Muster, keine Identitäten
Anonymisierte, strukturbezogene Signale.  
Nur technische Muster.

### 4.3 HRM darf keine Regeln erfinden
Es darf nur bestehende Regeln verfeinern.

### 4.4 HRM darf nie negativen Einfluss auf Wissen nehmen
Lernen muss immer Qualität erhöhen.

---

## 5. Sandbox-Beschränkungen

### 5.1 Keine autonomen Systeme
Sandbox darf:
- prüfen  
- vorschlagen  
- analysieren  
- optimieren  

Sandbox darf nicht:
- generieren  
- erstellen  
- verändern  
- löschen  

### 5.2 Vorschläge müssen deterministisch sein
Gleiche Eingabe → gleiche Ausgabe.

### 5.3 Keine spekulativen Kombinationen
Nur logisch ableitbare Vorschläge sind erlaubt.

---

## 6. Werkstatt-Beschränkungen

### 6.1 Werkstatt darf keine eigenen Regeln definieren
Sie ist reine Oberfläche, kein eigenständiges Regelwerk.

### 6.2 Werkstatt führt die Nutzerinteraktionen aus
Nicht mehr. Nicht weniger.

### 6.3 Werkstatt zeigt nur gültige Daten
Keine Zwischendaten. Keine wilden Roh-Stein-Fragmente.

---

## 7. Datenbeschränkungen

### 7.1 Versionierung ist Pflicht
Jeder Stein und jede Strukturänderung benötigt eine Version.

### 7.2 Quellenpflicht
Kein Stein ohne Quelle.

### 7.3 Keine Vermischung von Wissenstypen
Technisches Wissen bleibt technisch.  
Keine Meinungen, keine Interpretationen.

---

## 8. Systemerweiterungs-Beschränkungen

### 8.1 Erweiterungen dürfen den Kern nicht verändern
Steine, Graph, Sandbox, HRM, Werkstatt — unantastbare Kernmodule.

### 8.2 Erweiterungen müssen kompatibel bleiben
Backward-kompatibel, deterministisch und graph-aligned.

### 8.3 Erweiterungen dürfen keine konkurrierenden Wissenssysteme erzeugen
Keine Neben-Graphen, keine alternativen Steinformate.

---

## 9. Zusammenfassung

Diese architektonischen Constraints garantieren:

- Stabilität  
- Klarheit  
- Erweiterbarkeit  
- Konsistenz  
- Logische Integrität  
- Nutzerhoheit  

Sie schützen den Kern von MUNDUS und verhindern, dass das System durch Chaos, Overengineering oder unkontrollierte Erweiterungen beschädigt wird.

Ihre Einhaltung ist verpflichtend für alle zukünftigen Entwicklungen.

