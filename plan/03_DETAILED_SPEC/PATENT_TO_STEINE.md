# MUNDUS LAB — Patent → Steine (Zerlegungsspezifikation)

Dieses Dokument definiert den vollständigen Prozess, wie Patente, technische Dokumente und komplexe Texte in atomare Wissenseinheiten („Steine“) zerlegt werden.  
Der Prozess ist streng formalisiert, da er die Qualität des gesamten Systems bestimmt.

Die Zerlegung erzeugt Roh-Steine, die anschließend vom Nutzer validiert werden.

---

## 1. Prinzip der Zerlegung

Patente enthalten:
- Funktionen  
- Prinzipien  
- Mechanismen  
- Inputs  
- Outputs  
- Constraints  
- technische Bedingungen  
- Systembeschreibungen  
- Varianten  

Die Zerlegung trennt diese Inhalte in exakt **eine Aussage pro Stein**.

---

## 2. Schritte des Zerlegungsprozesses

### 2.1 Textsegmentierung
Der Patenttext wird in logische Segmente zerlegt:
- technische Aussagen  
- Funktionsbeschreibungen  
- Wirkungszusammenhänge  
- Mechanismusabschnitte  
- Lastfälle  
- Parameter  
- Bedingungen  

Nicht relevante Teile (z. B. juristische Formulierungen) werden ignoriert.

### 2.2 Extraktion von Kandidatenaussagen
Aus jedem Segment werden potenzielle Aussagen extrahiert:
- Was wird beschrieben?  
- Was bewirkt es?  
- Woraus besteht es?  
- Welche Bedingungen gelten?  
- Welche Abhängigkeiten bestehen?  

Jede Aussage wird als Stein-Kandidat markiert.

### 2.3 Kategorisierung (erste Vermutung)
Jeder Kandidatenstein erhält eine vorläufige Kategorie:
- funktion  
- prinzip  
- mechanismus  
- input  
- output  
- constraint  
- dependency  
- combinability  

Diese Klassifizierung ist oft fehleranfällig → Nutzer korrigiert.

### 2.4 Normalisierung
Der Text wird vereinfacht in klare Aussagen:
- Verkettungen werden entkoppelt  
- Nebensätze werden zu eigenen Steinen  
- komplexe Mechanismen werden in Teilmechanismen zerlegt  
- unpräzise Aussagen werden geschärft  

Beispiel:  
„Das System nutzt einen Hebel, der durch Federkraft aktiviert wird“  
→ wird zu mindestens **3 Steinen**.

### 2.5 Beziehungen ableiten
Zwischen Stein-Kandidaten werden erste Beziehungen erzeugt:
- nutzt  
- basiert_auf  
- teil_von  
- verlangt  
- erzeugt  
- alternative_zu  

Diese Beziehungen sind vorläufig.

### 2.6 Roh-Stein-Ergebnis
Nach Abschluss entsteht eine Liste von Roh-Steinen mit:
- Titel  
- vermuteter Kategorie  
- kurzer Beschreibung  
- rudimentären Beziehungen  
- Quelle (Patentnummer)  
- Version 0.1.0  

Diese Steine werden der Werkstatt zur Validierung gegeben.

---

## 3. Qualitätsregeln für die Zerlegung

### 3.1 Ein Stein = eine Aussage
Keine Mehrfachaussagen.

### 3.2 Keine Interpretationen
Nur explizite technische Aussagen des Dokuments.

### 3.3 Keine Schlussfolgerungen
Keine zusätzlichen technischen Bedeutungen hineininterpretieren.

### 3.4 Keine Vermischung der Kategorien
Jede Aussage wird in die einfachste Kategorie aufgeteilt.

### 3.5 Keine künstlichen Beziehungen
Nur direkte, explizite Zusammenhänge.

---

## 4. Typische Muster im Patenttext

### 4.1 Funktionsaussagen
„Das Gerät dient dazu…“  
→ funktion

### 4.2 Wirkprinzipien
„Durch Reibung wird…“  
→ prinzip

### 4.3 Mechanismen
„Ein Kolben bewegt sich innerhalb eines Zylinders…“  
→ mechanismus

### 4.4 Voraussetzungen
„Es ist erforderlich, dass…“  
→ requirement / dependency

### 4.5 Effekte
„Dadurch wird erreicht, dass…“  
→ output

### 4.6 Einschränkungen
„Der Druck darf 5 bar nicht überschreiten“  
→ constraint

---

## 5. Fehlerquellen und wie sie verhindert werden

### 5.1 Verschmolzene Aussagen
Muss zwingend getrennt werden.

### 5.2 Falsche Reihenfolge
Die zeitliche Reihenfolge im Patenttext ist irrelevant.  
Nur die logische Struktur zählt.

### 5.3 Juristische Formulierungen
Müssen konsequent ignoriert werden.

### 5.4 Uneinheitliche Schreibweise
Zerlegung normalisiert alle Formulierungen in technische Aussagen.

---

## 6. Validierung durch Nutzer

Roh-Steine werden in der Werkstatt überprüft:

- Typ korrigieren  
- Inhalt präzisieren  
- fehlende Felder ergänzen  
- unlogische Beziehungen entfernen  
- neue Beziehungen hinzufügen  

Validierte Steine werden mit Version 1.0.0 in den Graph übernommen.

---

## 7. Bedeutung des Prozesses

Die Zerlegung ist entscheidend für:

- Graphqualität  
- Sandboxtreue  
- HRM-Lernfähigkeit  
- Wissenspräzision  
- Skalierbarkeit  
- technische Nutzbarkeit  

Ohne korrekte Zerlegung entsteht kein nutzbarer Wissensgraph.

---

## 8. Zusammenfassung

Die Zerlegung macht aus komplexen Patenten:
- klare Steine  
- logische Strukturen  
- graphfähige Inhalte  
- analysierbare Mechanismen  
- kombinierbares Wissen  

Patente werden dadurch zu „Rohmaterial“, aus dem Nutzer präzise Wissenssteine formen können.

