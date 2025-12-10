# MUNDUS LAB — Versioning Strategy

Dieses Dokument beschreibt die vollständige Versionierungsstrategie für das gesamte MUNDUS-System.  
Versionierung stellt sicher, dass alle Änderungen nachvollziehbar, rückverfolgbar und reproduzierbar bleiben.  
Sie ist zwingend notwendig, da MUNDUS ein wachsendes, lebendiges Wissenssystem ist.

---

# 1. Grundprinzipien der Versionierung

### 1.1 Jede Änderung ist eine neue Version  
Es gibt keine stillen Änderungen — alles wird versioniert.

### 1.2 Versionen müssen nachvollziehbar sein  
Man muss immer wissen:
- was geändert wurde  
- warum es geändert wurde  
- von wem es geändert wurde  

### 1.3 Kernstrukturen haben strenge Regeln  
Steine, Graph, Sandbox und HRM müssen besonders präzise versioniert werden.

---

# 2. Versionierung von Steinen (Wissenseinheiten)

Steine verwenden **SemVer**:

`MAJOR.MINOR.PATCH`

### PATCH (x.x.1)
Wird erhöht bei:
- sprachlichen Präzisierungen  
- kleinen Klarheitskorrekturen  
- formatbezogenen Korrekturen  

### MINOR (x.1.x)
Wird erhöht bei:
- korrigierter Kategorie  
- neuer Beziehung  
- geänderter Beziehung  
- hinzugefügten technischen Details  
- inhaltlicher Erweiterung  

### MAJOR (1.x.x)
Extrem selten — nur wenn:
- ein Stein grundlegend neu definiert wird  
- eine technische Aussage ersetzt wird  
- Stein vollständig neu strukturiert werden muss  

### Startversion
`1.0.0` für validierte Steine  
`0.1.0` für Roh-Steine

---

# 3. Versionierung von Systemmodellen

Systemmodelle verwenden:

`SYSTEM_MAJOR.MINOR.PATCH`

### PATCH
- kleine Korrekturen in Ketten  
- Beziehungen aktualisiert  
- Constraints präzisiert  

### MINOR
- neue Mechanismen ergänzt  
- Alternativen hinzugefügt  
- System erweitert  

### MAJOR
- komplette Umstrukturierung  
- grundlegende Funktionsänderungen  

---

# 4. Versionierung des Wissensgraphen

Der Graph selbst erhält anstelle einer einfachen Versionsnummer:

### Graph Snapshot Version (GSV)

Beispiel:
`GSV-2025-01-14-A`

Ein Snapshot entsteht:
- täglich oder bei großen Änderungen  
- nach größeren Merge-Aktionen  
- nach Community-Batches  

Snapshots werden archiviert.

---

# 5. Versionierung der Sandbox

Sandbox hat eigene Regeln:

`SANDBOX_MAJOR.MINOR.PATCH`

PATCH  
- kleine Logikverbesserungen  
- effizientere Pfadprüfung  

MINOR  
- neue Konfliktmuster  
- neue Alternativregeln  
- neue Kompatibilitätschecks  

MAJOR  
- strukturelle Erweiterung der gesamten Logik  
- neue Analyse-Subsysteme  

Die Sandbox darf nie unsichtbar geändert werden.

---

# 6. Versionierung des HRM

HRM wird extrem vorsichtig versioniert, da es lernende Parameter enthält.

Versionierung:

`HRM_MAJOR.MINOR.PATCH`

PATCH  
- kleine Gewichtungsupdates  
- bessere Signalfilter  
- kleinere Lernkorrekturen  

MINOR  
- neue Arten von Lernsignalen  
- neue Verstärkungs-/Abschwächungsregeln  

MAJOR  
- fundamentale Änderungen der Lernarchitektur  

Jede HRM-Version muss auditierbar sein.

---

# 7. Versionierung der Dokumentation

Dokumente werden versioniert über Git-Historie,  
aber zusätzlich mit dem Header:

`Doc-Version: x.x.x`

### PATCH
- kleine Klarstellungen  
- Tippfehler  
- Formatkorrekturen  

### MINOR
- neue Abschnitte  
- strukturierte Erweiterungen  

### MAJOR
- komplette Neufassung  

---

# 8. Projektweite Versionierung

Das gesamte Projekt hat eine Hauptversionsnummer:

`MUNDUS_MAJOR.MINOR.PATCH`

Diese Version repräsentiert den **Reifegrad des gesamten Systems**.

### Beispielstufen
- 0.x.x → Experimentelle Phase  
- 1.x.x → MVM abgeschlossen  
- 2.x.x → stabiler Graph  
- 3.x.x → erweiterte Werkstatt  
- 4.x.x → Simulation integriert  
- 5.x.x → globale Technologie-Karte  
- 6.x.x → ökosystemfähig  

---

# 9. Upgrade-Regeln

### 9.1 Kein Mischstatus
Steine, Sandbox, HRM und Graph müssen kompatibel sein.

### 9.2 Keine Rückwärtsbrüche ohne MAJOR
Nur MAJOR-Version darf inkompatible Änderungen bringen.

### 9.3 Automatische Migration
System muss kleine Updates automatisch übernehmen können.

### 9.4 Änderungslogbuch
Jede Version muss in **/plan/07_META/CHANGELOG.md** eingetragen werden.

---

# 10. Zusammenfassung

Die Versionierungsstrategie stellt sicher:

- vollständige Nachvollziehbarkeit  
- hohe Systemqualität  
- stabile Weiterentwicklung  
- klare Abgrenzung von Änderungen  
- auditierbare Lernprozesse  
- Reproduzierbarkeit technischer Zustände  

Versionierung ist ein zentrales Sicherheits- und Qualitätsinstrument  
für das gesamte MUNDUS-Projekt.

