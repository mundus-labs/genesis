# MUNDUS LAB — System Requirements

Dieses Dokument definiert alle Anforderungen an das MUNDUS-System.  
Es unterscheidet zwischen funktionalen und nicht-funktionalen Anforderungen  
und beschreibt, was MUNDUS unbedingt können muss, damit es stabil, logisch, skalierbar und nutzerfreundlich bleibt.

Die Anforderungen gelten für das gesamte System – nicht nur für das MVM.

---

# 1. Funktionale Anforderungen (Functional Requirements)

## 1.1 Patent- und Textaufnahme
- System muss Patente und technische Dokumente einlesen können.  
- System muss Texte segmentieren und analysieren.  
- System muss daraus Roh-Steine erzeugen.  

## 1.2 Roh-Stein-Erzeugung (Decomposition Engine)
- Roh-Steine müssen automatisch generiert werden.  
- Jeder Roh-Stein muss Typ-Vermutung enthalten.  
- Roh-Steine müssen in der Werkstatt bearbeitbar sein.  

## 1.3 Stein-Validierung
- Nutzer muss Inhalte korrigieren können.  
- Nutzer muss Kategorien zuweisen können.  
- Nutzer muss Beziehungen bearbeiten können.  
- System muss Steinformat prüfen.  
- Versionierung muss automatisch erzeugt werden.  

## 1.4 Wissensgraph
- System muss validierte Steine als Graph speichern.  
- Knoten (Steine) und Kanten (Beziehungen) müssen manipulierbar sein.  
- Graphnavigation muss möglich sein.  
- Cluster müssen erkennbar sein.  

## 1.5 Werkstatt (Workshop)
Werkstatt muss:
- Steine anzeigen  
- Steine vergleichen  
- Steine kombinieren  
- Systeme analysieren  
- Fehler anzeigen  
- Alternativen vorschlagen  

## 1.6 Sandbox
Die Sandbox muss:
- Kompatibilität prüfen  
- Konflikte erkennen  
- Alternativen finden  
- fehlende Steine anzeigen  
- Erklärungen liefern  
- deterministisch arbeiten  

## 1.7 HRM (Learning Core)
HRM muss:
- Nutzersignale sammeln  
- Korrekturen verarbeiten  
- Vorschlagsannahmen lernen  
- Ablehnungen lernen  
- Kombinationen gewichten  
- Zerlegungsregeln verbessern  

## 1.8 UI / Interface Logic
UI muss:
- klar strukturiert sein  
- reversibel sein  
- intuitive Bedienung bieten  
- Warnungen und Konflikte anzeigen  
- Sandbox-Vorschläge anzeigen  
- Fokusobjekt hervorheben  

---

# 2. Nicht-funktionale Anforderungen (Non-Functional Requirements)

## 2.1 Stabilität
- System darf niemals abstürzen.  
- Kernfunktionen müssen deterministisch arbeiten.  
- HRM und Sandbox dürfen keine Daten verfälschen.  

## 2.2 Performance
- Steine müssen sofort geladen werden.  
- Graph muss flüssig navigierbar sein.  
- Sandbox-Antwortzeit < 0.5 Sekunden (für MVM).  

## 2.3 Skalierbarkeit
- Graph muss Millionen von Steinen verarbeiten können.  
- HRM muss kontinuierlich mitwachsen können.  
- Werkstatt muss große Systeme darstellen können.  

## 2.4 Sicherheit
- kein Speichern persönlicher Nutzerdaten  
- kein Tracking von Identitäten  
- vollständige Datenkontrolle durch Nutzer  

## 2.5 Transparenz
- jede Empfehlung muss erklärbar sein  
- jede Graphbeziehung muss sichtbar sein  
- jede HRM-Anpassung muss nachvollziehbar sein  

## 2.6 Wiederherstellbarkeit
- Versionierung muss vollständig sein  
- Änderungen müssen rückgängig gemacht werden können  
- Graphkorrekturen dürfen nie Daten zerstören  

## 2.7 Erweiterbarkeit
- neue UI-Funktionen dürfen Kernlogik nicht verletzen  
- neue HRM-Algorithmen müssen kompatibel sein  
- neue Sandbox-Regeln müssen deterministisch sein  

---

# 3. Systemverhalten unter Last

## 3.1 Bei sehr vielen Steinen
- automatische Clustering-Mechanismen  
- lazy loading  
- Begrenzung der Visualisierung, nicht der Daten  

## 3.2 Bei intensiver Nutzung
- HRM muss robust aggregieren  
- Sandbox darf nicht langsamer werden  
- Werkstatt muss stabil bleiben  

---

# 4. Qualitätsanforderungen

## 4.1 Datenqualität
- Steine müssen validiert sein  
- Beziehungen müssen logisch sein  
- keine Spekulationen im Graph  

## 4.2 Codequalität (für Implementierung später)
- Module müssen klar getrennt sein  
- Keine Hidden Dependencies  
- deterministisches Verhalten  
- volle Testabdeckung  

## 4.3 UX-Qualität
- Nutzer muss immer wissen, wo er ist  
- UI darf niemals überladen wirken  
- Fehler müssen sichtbar und erklärbar sein  

---

# 5. Zusammenfassung

MUNDUS muss folgende Dinge absolut zuverlässig erfüllen:

- Wissen aufnehmen  
- Wissen zerlegen  
- Wissen validieren  
- Wissen graphbasiert strukturieren  
- Wissen analysieren  
- Wissen kombinieren  
- Wissen verbessern  
- Wissen nutzbar machen  
- Wissen verständlich darstellen  

Diese Anforderungen definieren den technischen Rahmen und sind nicht verhandelbar.

