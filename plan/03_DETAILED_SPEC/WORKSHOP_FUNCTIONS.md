# MUNDUS LAB — Workshop Functions

Die Werkstatt (Workshop) ist die Hauptschnittstelle zwischen Nutzer und System.  
Hier findet technische Analyse, Konstruktion, Korrektur und Exploration statt.  
Das folgende Dokument beschreibt alle Funktionen, die die Werkstatt bereitstellt.

---

## 1. Grundfunktionen der Werkstatt

Die Werkstatt bietet fünf Hauptfunktionalitäten:

1. Einzelstein-Anzeige  
2. Vergleich von Steinen  
3. Kombination von Steinen  
4. Analyse bestehender Systeme  
5. Exploration des Wissensgraphen  

Diese Funktionen bilden das Herzstück der Nutzerinteraktion.

---

## 2. Einzelstein-Anzeige (Stone View)

### 2.1 Funktion
Zeigt alle Informationen eines Steins:

- Titel  
- Typ  
- Summary  
- Details  
- Requirements  
- Results  
- Beziehungen (Kanten im Graph)  
- Quelle  
- Version  

### 2.2 Zusatzfunktionen
- Beziehungen anklickbar  
- Navigation zu verbundenen Steinen  
- Schnellkorrekturen möglich  

### 2.3 Bedeutung
Dient dem Verständnis einzelner Wissenseinheiten.

---

## 3. Vergleichsansicht (Comparison View)

### 3.1 Funktion
Vergleicht zwei oder mehr Steine:

- Inhaltliche Unterschiede  
- kategoriale Unterschiede  
- verschiedenartige Mechanismen  
- alternative Lösungen  
- Konflikte  

### 3.2 typische Anwendungsfälle
- Alternative Mechanismen finden  
- Funktionsprinzipien vergleichen  
- Auswahl optimaler Steinvarianten  

---

## 4. Kombinationsansicht (Combination View)

### 4.1 Funktion
Nutzer können Steine logisch miteinander verbinden:

- Input → Output Matching  
- Mechanismus + Prinzip  
- Funktion → Mechanismuskette  

### 4.2 Sandbox-Unterstützung
Die Sandbox liefert automatisch:
- Vorschläge  
- Alternativen  
- Konfliktwarnungen  
- fehlende Elemente  

### 4.3 Ziel
Bau technischer Systeme aus atomaren Wissenseinheiten.

---

## 5. Systemanalyse (System Analyzer)

### 5.1 Funktion
Analyse kompletter Konstruktionen:

- Kompatibilitätsprüfung  
- Constraint-Check  
- Dependency-Check  
- Lückenanalyse  
- alternative Mechanismen  
- Optimierungswege  

### 5.2 Ergebnis
Der Nutzer erhält eine vollständige Übersicht:
- gültig/ungültig  
- was fehlt  
- was besser geht  

---

## 6. Explorationsmodus (Graph Exploration)

### 6.1 Funktion
Visuelle Navigation durch den Wissensgraph:

- Anzeige von Knoten (Steinen)  
- Anzeige von Beziehungen  
- Cluster und Themenbereiche  
- technische Pfade  

### 6.2 Werkzeuge
- Zoom  
- Filter  
- Pfadfinder  
- Alternativensucher  

### 6.3 Wert
Erkenntnisse durch Navigieren technischer Strukturen.

---

## 7. Korrekturmodus (Correction Mode)

### 7.1 Funktion
Nutzer können jeden Aspekt eines Steins bearbeiten:

- Kategorie korrigieren  
- summary verbessern  
- details präzisieren  
- requirements ergänzen  
- results korrigieren  
- Beziehungen löschen  
- Beziehungen hinzufügen  

### 7.2 HRM-Integration
Jede Korrektur fließt ins Human Reward Model ein.

### 7.3 Bedeutung
Zentrale Qualitätskontrolle des Systems.

---

## 8. Stein-Erstellung (Stone Creator)

### 8.1 Funktion
Nutzer kann neue Steine anlegen:

- komplett manuell  
- basierend auf Vorlage  
- basierend auf bestehendem Stein  
- basierend auf identifizierter Lücke  

### 8.2 Prüfung
Jeder neue Stein muss sofort dem Steinformat entsprechen.

---

## 9. System-Konstruktionstools (Builder Functions)

### 9.1 Drag-and-Drop-Konstruktion
Nutzer zieht Steine in den Bau-Bereich.

### 9.2 Verbindungsresonanz
Werkstatt zeigt sofort:
- passt / passt nicht  
- Konflikt / keine Konflikte  
- Alternativen  

### 9.3 Pfadvorschläge
Werkstatt nutzt Sandbox, um mögliche Funktionsketten vorzuschlagen.

---

## 10. Historie & Change Tracking

### 10.1 Änderungslogik
Werkstatt zeigt:
- was verändert wurde  
- von wem  
- wann  
- welche Version vorher existierte  

### 10.2 Revert-Funktionen
Nutzer kann Änderungen rückgängig machen.

---

## 11. Qualitätsmechanismen

Die Werkstatt schützt Systemqualität durch:
- Validierungschecks  
- Warnungen bei Mehrfachaussagen  
- Hinweis auf fehlende Felder  
- Konfliktkennzeichnung  
- Nichtzulassen fehlerhafter Steine  

---

## 12. Integration mit anderen Modulen

### 12.1 Werkstatt ↔ Sandbox
- Konstruktionen → Analyse  
- Analyse → Vorschläge  

### 12.2 Werkstatt ↔ Graph
- Navigation → Graph  
- Graph → Werkstattvisualisierung  

### 12.3 Werkstatt ↔ HRM
- Korrekturen → Lernsignale  
- Annahmen/Ablehnungen → Verstärkungen  

---

## 13. Zusammenfassung

Die Werkstatt:
- ist die zentrale Nutzerschnittstelle  
- ermöglicht Steinverständnis  
- unterstützt Systemkonstruktion  
- prüft technische Logik  
- erlaubt Korrekturen  
- speist HRM  
- nutzt den Graph  
- wird durch Sandbox intelligent unterstützt  

Sie ist das praktische Herz von MUNDUS –  
der Raum, in dem Wissen in echte Technologie übersetzt wird.

