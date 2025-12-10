# MUNDUS LAB — Steinformat (MMF Specification)

Dieses Dokument definiert das exakte Format eines Steins.  
Jeder Stein muss strikt dieser Struktur folgen, damit er:
- maschinenlesbar,
- vergleichbar,
- kombinierbar,
- versionierbar
bleibt.

Das Steinformat ist eine unveränderbare Kernkomponente von MUNDUS.

---

## 1. Grundidee des Formats

Ein Stein beschreibt genau **eine** technische Aussage.  
Die Struktur ist minimal, aber vollständig genug, um Logik, Kombination und Analyse zu ermöglichen.

Jeder Stein enthält:
- Metadaten,
- Inhalt,
- Beziehungen,
- Versionierung.

---

## 2. Steinstruktur (MMF)

Jeder Stein besteht aus den folgenden Feldern:

### 2.1 Titel (title)
Kurze, eindeutige Beschreibung der Aussage.  
Maximal ein Satz.

### 2.2 Kategorie (type)
Eine der acht MMF-Kategorien:
- funktion  
- prinzip  
- mechanismus  
- input  
- output  
- constraint  
- dependency  
- combinability  

Keine weiteren Kategorien sind erlaubt.

### 2.3 Kurzbeschreibung (summary)
Ein bis zwei Sätze, die die Aussage präzise erklären.

### 2.4 Details (details) — optional
Vertiefte technische Beschreibung, falls nötig.  
Darf nicht mehrere Aussagen kombinieren.

### 2.5 Anforderungen (requirements)
Alles, was notwendig ist, damit der Stein gültig ist.
Beispiele:
- benötigte Inputs  
- notwendige Bedingungen  
- voraussetzende Mechanismen  

### 2.6 Ergebnisse (results)
Outputs, Effekte oder Konsequenzen der Aussage.

### 2.7 Beziehungen (relations)
Liste logisch begründeter Verbindungen zu anderen Steinen.

Erlaubte Beziehungstypen:
- nutzt  
- basiert_auf  
- teil_von  
- alternative_zu  
- erweitert  
- ersetzt  
- verlangt  
- erzeugt  

Jede Beziehung enthält:
- Beziehungstyp  
- Ziel-Stein-ID  

### 2.8 Quelle (source)
Verweis auf Ursprung:
- Patentnummer  
- Dokument  
- Nutzer  
- Datenquelle  

### 2.9 Version (version)
Version des Steins im Format:
**MAJOR.MINOR.PATCH**

Beispiele:
- 1.0.0 = erste stabile Version  
- 1.1.0 = neue Informationen hinzugefügt  
- 1.1.1 = Fehler in summary korrigiert  

---

## 3. Regeln für die Erstellung von Steinen

### 3.1 Ein Stein = eine Aussage
Keine Kombinationen, keine Absätze, keine Mehrfachaussagen.

### 3.2 Kategorien dürfen nie gemischt werden
Der Stein muss eindeutig sein.

### 3.3 Kurzbeschreibung muss verständlich sein
Ohne Abkürzungen, ohne unpräzise Formulierungen.

### 3.4 Keine irrelevanten Details
Nur technische Aussagen und notwendige Informationen.

### 3.5 Jede Beziehung muss logisch begründet sein
Keine spekulativen Verbindungen.

### 3.6 Quelle ist Pflicht
Ohne Quelle kein gültiger Stein.

### 3.7 Versionierung ist Pflicht
Jede Änderung muss nachvollziehbar sein.

---

## 4. Beispiel eines vollständig validierten Steins

Titel: "Ein Hebel vergrößert eine Kraft durch verlängerten Weg."  
Typ: prinzip  
Summary: "Das Hebelgesetz beschreibt, wie eine kleine Kraft durch größere Distanz vervielfacht werden kann."  
Details: "Der mechanische Vorteil ergibt sich aus dem Verhältnis zwischen Lastarm und Kraftarm."  
Requirements: "Es muss ein Drehpunkt existieren."  
Results: "Erhöhte Kraftwirkung am Lastarm."  
Relations:
- basiert_auf: "mechanik_drehpunkt_prinzip"
- teil_von: "mechanik_hebel_system"
Source: "Lehrbuch Mechanik, Kap. 2"  
Version: 1.0.1  

---

## 5. Validierungskriterien

Ein Stein ist **gültig**, wenn:
- alle Pflichtfelder vorhanden sind  
- Kategorie korrekt ist  
- summary die Aussage klar enthält  
- keine zweite Aussage versteckt ist  
- Beziehungen logisch korrekt sind  
- Version gesetzt ist  
- Quelle angegeben ist  

Ein Stein ist **ungültig**, wenn:
- er zwei oder mehr Aussagen kombiniert  
- Typ oder Inhalt nicht übereinstimmen  
- Beziehungen nicht begründet sind  
- Inhalte spekulativ sind  
- Quelle fehlt  
- Format verletzt wird  

---

## 6. Bedeutung des Formats

Das Format garantiert:
- Interoperabilität aller Komponenten  
- maschinelle Auswertbarkeit  
- zuverlässige Sandbox-Analysen  
- HRM-Lernfähigkeit  
- Graph-Stabilität  
- Skalierbarkeit des gesamten Projekts  

Ohne ein strenges Format wäre MUNDUS nicht funktionsfähig.

---

## 7. Zusammenfassung

Ein Stein ist eine präzise, normierte Wissenseinheit.  
Das Steinformat ist die Struktur, die MUNDUS stabil, erweiterbar und logisch hält.

Diese Spezifikation darf nie aufgeweicht werden.
