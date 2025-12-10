# MUNDUS LAB — Validation Workflow

Dieses Dokument beschreibt den gesamten Validierungsprozess, der aus automatisch erzeugten Roh-Steinen vollständig geprüfte, korrigierte und in den Graph integrierbare Steine macht.  
Der Validierungsworkflow garantiert die Qualität, Präzision und technische Verwendbarkeit der Wissenseinheiten in MUNDUS.

Der Prozess kombiniert automatische Vorarbeit, menschliche Expertise und lernfähige Optimierung durch das HRM.

---

## 1. Ziel des Validierungsprozesses

Der Validierungsworkflow soll sicherstellen, dass:

- jeder Stein korrekt kategorisiert ist  
- nur eine einzelne technische Aussage enthält  
- alle Felder vollständig und logisch sind  
- Beziehungen technisch sinnvoll sind  
- keine spekulativen Aussagen eingefügt werden  
- die Struktur mit dem MUNDUS-Format übereinstimmt  

Validierung ist notwendig, bevor ein Stein in den Wissensgraph aufgenommen wird.

---

## 2. Ausgangspunkt: Roh-Steine

Roh-Steine entstehen durch:
- automatische Zerlegung von Patenten  
- Extraktion aus technischen Texten  
- systemgenerierte Vorschläge  

Sie enthalten:
- vorläufige Typvermutung  
- grobe Beschreibung  
- mögliche Beziehungen  
- Quelle  
- Version 0.1.0  

Roh-Steine sind **nicht** graphfähig.

---

## 3. Validierungsschritte

### 3.1 Sichtprüfung durch den Nutzer
Nutzer überprüft:
- Ist die Aussage klar?  
- Ist der Typ korrekt?  
- Enthält der Stein mehrere Aussagen?  
- Sind Begriffe sauber formuliert?  

Fehler werden direkt korrigiert.

### 3.2 Typzuweisung (MMF-Kategorie)
Der Nutzer wählt korrekte Kategorie:

- funktion  
- prinzip  
- mechanismus  
- input  
- output  
- constraint  
- dependency  
- combinability  

Falsche Typen sind die häufigste Fehlerquelle.

### 3.3 Inhaltliche Korrektur
Der Nutzer präzisiert:
- summary  
- details  
- requirements  
- results  

Ziel: technische Aussage eindeutig und vollständig machen.

### 3.4 Strukturprüfung
Der Stein muss:
- einheitlich formatiert  
- vollständig ausgefüllt  
- logisch konsistent  
sein.

Fehlt ein Pflichtfeld → Stein ist unvollständig.

### 3.5 Beziehungsprüfung
Nutzer prüft vorgeschlagene Beziehungen:
- falsch → löschen  
- richtig → bestätigen  
- fehlend → ergänzen  

Erlaubte Beziehungstypen siehe Graph Relations.

### 3.6 Quellenprüfung
Jeder Stein muss eine gültige Quelle besitzen:
- Patentnummer  
- Dokument  
- Nutzerwissen  

Ohne Quelle → ungültig.

### 3.7 Version setzen
Nach Validierung wird Version gesetzt:
**1.0.0** = gültiger Stein

Weitere Änderungen:
- 1.1.x für Erweiterungen  
- 1.0.x für Korrekturen  

---

## 4. Qualitätskriterien für Validierung

Ein Stein ist validiert, wenn:

- er nur eine Aussage enthält  
- Kategorie eindeutig ist  
- summary korrekt ist  
- details optional, aber klar sind  
- requirements und results logisch sind  
- Beziehungen sinnvoll sind  
- Quelle gesetzt ist  
- Version korrekt gesetzt wurde  

Ein Stein ist **nicht** validiert, wenn:
- Aussagen vermischt sind  
- Kategorie unklar ist  
- spekulative Inhalte enthalten sind  
- Beziehungen nicht stimmen  
- keine Quelle vorhanden ist  
- Format verletzt wird  

---

## 5. Übergang in den Wissensgraph

Sobald ein Stein validiert wurde, wird er:
- als Knoten in den Graph eingefügt  
- mit den bestätigten Beziehungen verbunden  
- in Cluster einsortiert  
- sofort in Werkstatt und Sandbox nutzbar  

**Nur validierte Steine** dürfen in den Graph gelangen —  
dies schützt die gesamte Systemintegrität.

---

## 6. HRM-Lernen im Validierungsprozess

HRM lernt aus:
- jeder Typkorrektur  
- jeder inhaltlichen Korrektur  
- jeder Beziehungskorrektur  
- jeder bestätigten Beziehung  
- jeder Ablehnung einer falschen Beziehung  

HRM nutzt diese Muster für:
- bessere Zerlegung  
- bessere Klassifizierung  
- bessere Beziehungsvorschläge  
- bessere Sandboxresultate  

---

## 7. Validierungscycle (Ablaufsequenz)

1. Roh-Stein generiert  
2. Nutzer prüft Inhalt  
3. Nutzer korrigiert Typ  
4. Nutzer präzisiert summary/details  
5. Nutzer korrigiert Beziehungen  
6. Nutzer ergänzt fehlende Felder  
7. Quelle bestätigen  
8. Version 1.0.0 setzen  
9. Stein in Graph übernehmen  

Dieser Ablauf ist zwingend — keine Abkürzungen.

---

## 8. Bedeutung des Validierungsprozesses

Validierung sorgt für:
- maximale Datenqualität  
- transparente Logik  
- stabile Sandbox-Vorschläge  
- zuverlässigen Graph  
- skalierbares Wissen  
- lernfähiges HRM  

Ohne Validierung würde das gesamte MUNDUS-System unbrauchbar werden.

---

## 9. Zusammenfassung

Der Validierungsworkflow macht aus Rohdaten:
- klare Steine  
- zuverlässige Strukturen  
- graphfähiges Wissen  
- systemweit nutzbare technische Einheiten  

Er ist das Qualitätsfundament von MUNDUS.

