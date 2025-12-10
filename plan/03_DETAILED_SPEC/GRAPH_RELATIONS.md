# MUNDUS LAB — Graph Relations (Beziehungsdefinitionen)

Dieses Dokument beschreibt alle zulässigen Beziehungstypen im MUNDUS-Wissensgraphen, ihre Bedeutung, Regeln, Einschränkungen und Anwendungsfälle.  
Der Graph ist das strukturelle Rückgrat des Systems, und seine Beziehungen bestimmen, wie Wissen verknüpft, navigiert, kombiniert und analysiert wird.

Alle Beziehungen müssen technisch begründet und logisch nachvollziehbar sein.

---

## 1. Grundidee

Jeder Stein ist ein Knoten.  
Jede Beziehung zwischen zwei Steinen ist eine gerichtete oder ungerichtete Kante.

Beziehungen definieren:
- Funktionsketten  
- Abhängigkeiten  
- Mechanismen  
- Systemstrukturen  
- Alternativen  
- Hierarchien  

Nur klar definierte Beziehungstypen sind erlaubt.

---

## 2. Zulässige Beziehungstypen

### 2.1 nutzt
Ein Mechanismus oder Funktion verwendet ein Prinzip, Material oder anderes Element.

Beispiel:
- „Hebel nutzt Drehpunktprinzip“

### 2.2 basiert_auf
Eine höhere Funktion stützt sich auf einen zugrunde liegenden Mechanismus oder ein Prinzip.

Beispiel:
- „Kraftverstärkung basiert_auf Hebelgesetz“

### 2.3 teil_von
Ein Stein ist Bestandteil eines komplexeren Mechanismus oder Systems.

Beispiel:
- „Kolben ist teil_von Hydraulikzylinder“

### 2.4 alternative_zu
Ein Stein erfüllt dieselbe Funktion oder nutzt dasselbe Prinzip, aber auf andere Weise.

Beispiel:
- „Schraubgetriebe alternative_zu Keilmechanismus“

### 2.5 erweitert
Ein Mechanismus oder Prinzip ist eine präzisere Version eines bestehenden Steins.

Beispiel:
- „Planetengetriebe erweitert Stirnradgetriebe“

### 2.6 ersetzt
Ein Stein kann funktional an die Stelle eines anderen treten.

Beispiel:
- „Elektrischer Aktor ersetzt hydraulischen Aktor“

### 2.7 verlangt
Ein Mechanismus oder Prozess benötigt bestimmte Inputs, Bedingungen oder Abhängigkeiten.

Beispiel:
- „Hydrauliksystem verlangt Druckquelle“

### 2.8 erzeugt
Ein Mechanismus liefert einen Output oder Zustand.

Beispiel:
- „Kompressor erzeugt Überdruck“

---

## 3. Regeln für Beziehungen

### 3.1 Beziehungen müssen eindeutig sein
Jede Beziehung muss:
- klar nachvollziehbar  
- technisch korrekt  
- logisch begründet  
sein.

### 3.2 Keine Vermischung von Beziehungstypen
Ein Zusammenhang darf nur einen Typ haben.  
Mehrdeutige Beziehungen müssen getrennt werden.

### 3.3 Keine spekulativen Beziehungen
Nur Aussagen, die explizit:
- im Patent,
- im technischen Text,
- in der Konstruktion,
- oder durch Nutzerlogik begründet sind

dürfen als Beziehung gespeichert werden.

### 3.4 Beziehungen dürfen nicht zirkulär spekulativ werden
Zirkeln wie A basiert_auf B, B basiert_auf A sind nicht erlaubt.

### 3.5 Beziehungen müssen minimal sein
Keine überflüssigen Kanten, keine doppelten Aussagen.

### 3.6 Nutzer haben Priorität
Wenn Nutzer eine Beziehung löscht → Beziehung ist ungültig.  
Wenn Nutzer hinzufügt → Beziehung wird aufgenommen.  
HRM lernt daraus.

---

## 4. Entstehung von Beziehungen

### 4.1 Automatische Erzeugung (Rohphase)
Zerlegung extrahiert potenzielle Beziehungen.  
Diese sind oft fehlerhaft und müssen validiert werden.

### 4.2 Nutzerkorrektur
Die wichtigste Quelle für korrekte Beziehungen.

### 4.3 HRM-Lernen
Wenn Nutzer wiederholt:
- denselben Steinpfad gehen,
- dieselbe Kombination bauen,
- Vorschläge annehmen,
- Alternativen nutzen,

erkennt HRM Muster und verbessert zukünftige Vorschläge.

### 4.4 Sandbox-Analyse
Sandbox kann fehlende Beziehungen vorschlagen, aber niemals autonom einfügen.

---

## 5. Beziehungskategorien nach Funktion

### 5.1 Strukturelle Beziehungen
- teil_von  
- erweitert  
- ersetzt  

### 5.2 Funktionsbezogene Beziehungen
- nutzt  
- basiert_auf  
- erzeugt  

### 5.3 Bedingungsbezogene Beziehungen
- verlangt  
- dependency-ähnliche Strukturen  

### 5.4 Variantenbeziehungen
- alternative_zu  

---

## 6. Bedeutung im Wissensgraph

Beziehungen ermöglichen:
- logische Pfade  
- Technologie-Landschaften  
- Funktionsketten  
- Systemzerlegung  
- Variantenvergleich  
- technisches Clustering  
- Konflikterkennung  
- Vorschlagslogik für Sandbox  

Ohne korrekte Beziehungen entsteht kein nutzbarer Graph.

---

## 7. Qualitätskriterien für gültige Beziehungen

Eine Beziehung ist gültig, wenn:
- sie technisch korrekt ist  
- sie auf Dokument oder Nutzerverstand basiert  
- sie nicht redundant ist  
- sie nicht widersprüchlich ist  
- sie genau einen Beziehungstyp verwendet  
- sie erklärbar ist  

Eine Beziehung ist ungültig, wenn:
- sie aus Vermutung entsteht  
- sie mehrfach interpretiert werden kann  
- sie zwei unterschiedliche Bedeutungen hat  
- sie auf spekulativer Ableitung beruht  
- sie Kategorien verletzt  

---

## 8. Zusammenfassung

Beziehungen sind das strukturelle Fundament des MUNDUS-Wissensgraphen.  
Sie verbinden Steine zu einem logischen, navigierbaren und lernfähigen Netzwerk.

Nur sauber definierte Beziehungen garantieren:
- stabile Sandbox  
- sinnvolle Vorschläge  
- präzises HRM-Lernen  
- verständliche Werkstatt  
- skalierbares Gesamtsystem  

Die Einhaltung dieser Spezifikation ist verpflichtend.

