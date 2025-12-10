# MUNDUS LAB — Interface Logic

Dieses Dokument beschreibt die grundlegende Logik der Benutzeroberfläche von MUNDUS.  
Es definiert, wie Elemente reagieren, wie Interaktionen verarbeitet werden und wie das System Nutzeraktionen interpretiert.  
Die Interface Logic stellt sicher, dass das UI klar, nachvollziehbar, stabil und logisch konsistent bleibt.

---

## 1. Grundprinzipien der UI-Logik

### 1.1 Klarheit vor Komplexität  
Alles muss sofort verständlich sein.  
Die Oberfläche zeigt nur das, was notwendig ist.

### 1.2 Jede Aktion ist explizit  
Keine versteckten Aktionen, keine automatischen Zustandswechsel.

### 1.3 Alles ist rückgängig machbar  
Benutzer müssen jederzeit zurückspringen können.

### 1.4 Keine Mehrdeutigkeit  
Jeder Button, jedes Panel, jeder Zustand hat nur EINE eindeutige Bedeutung.

### 1.5 UI zeigt nur gültiges Wissen  
Rohdaten, Fehlerzustände oder unstrukturierte Informationen werden NIEMALS angezeigt.

---

## 2. UI-Hauptbereiche

### 2.1 Linke Seitenleiste (Navigation)
Enthält:
- Suche  
- Filter  
- Kategorien  
- persönliche Listen  
- offene Steine  
- zuletzt verwendete Elemente  

Regeln:
- Keine tiefen verschachtelten Menüs  
- Maximal 2 Ebenen  

### 2.2 Hauptarbeitsbereich (Canvas)
Wird verwendet für:
- Steinansicht  
- Systembau  
- Analyse  
- Vergleich  
- Graphvisualisierung  

Regeln:
- Immer maximal ein Fokusobjekt  
- Nebenobjekte erscheinen rechts oder unten, nie im Hauptbereich  

### 2.3 Rechte Werkzeugleiste (Werkzeuge)
Tools für:
- Korrektur  
- Verbindungen  
- Analysefunktionen  
- Vorschläge  
- Optimierung  

Regeln:
- Tools ändern NIE automatisch den Inhalt  
- Tools zeigen Warnungen und Vorschläge, aber entscheiden nicht  

---

## 3. Interaktionsregeln

### 3.1 Klick auf Stein
Öffnet Steinansicht im Hauptbereich.  
Graph oder Listen bleiben sichtbar.

### 3.2 Klick auf Beziehung
Springt zu Zielstein.  
Breadcrumb oben aktualisiert sich.

### 3.3 Drag-and-Drop
Erlaubt:
- Steine in den Bau-Bereich ziehen  
- Beziehungen visualisieren  
- Pfade darstellen  

Regel:
- Sandbox prüft Kombination erst NACH dem Loslassen.

### 3.4 Doppelklick auf Mechanismus
Öffnet Funktionskette oder Subsystem.

### 3.5 Korrekturen
Jede Änderung öffnet ein „Speichern“-Banner.  
Nutzer muss aktiv speichern.

---

## 4. Sichtbarkeitsregeln

### 4.1 Nur validierte Steine sichtbar
Ungültige Roh-Steine werden separat angezeigt.

### 4.2 Fehler und Konflikte deutlich markieren
Konflikt → rot  
Fehlender Stein → gelb  
Alternative → blau  

### 4.3 Beziehungen im Graph
- starke Beziehung = dicker Strich  
- schwache Beziehung = dünn  
- alternative_zu = gestrichelt  

### 4.4 Fokusregel
Nur EIN Inhalt darf den zentralen Fokus haben.  
Niemals zwei gleichberechtigte Inhalte parallel.

---

## 5. Zustandsmanagement

### 5.1 Offen/geschlossen Logik
UI kennt nur zwei Zustände:
- offen  
- geschlossen  

Keine Zwischenzustände.

### 5.2 Persistenz
Zuletzt geöffnete Steine werden gespeichert.  
Zuletzt erstellte Systeme werden automatisch geladen.

### 5.3 Revertierbarkeit
Jede Aktion kann rückgängig gemacht werden:
- Steinänderungen  
- Systembau  
- Beziehungskorrekturen  

---

## 6. Vorschlagslogik im UI

### 6.1 Sandbox-Vorschläge erscheinen immer rechts
Nie im Hauptbereich.  
Nie als Popup.

### 6.2 Vorschläge müssen eine Begründung anzeigen
UI zeigt:
- Pfad  
- relevante Steine  
- Constraints  
- Alternativen  

### 6.3 Nutzer muss aktiv auswählen
Keine Auto-Annahmen.

---

## 7. Fehlermeldungen & Warnungen

### 7.1 Sofortige Rückmeldung
Wenn:
- Constraint verletzt  
- Dependency fehlt  
- Typ falsch  
- Formatfehler  

erscheinen Warnungen mit klarer Ursache.

### 7.2 Nie kryptische Fehlermeldungen
Fehler müssen erklärt werden:
- Problem  
- Grund  
- möglicher Fix  

---

## 8. Graph-Interaktion

### 8.1 Hover zeigt Kurzinfos  
Typ, Titel, Beziehungen.

### 8.2 Klick = Öffnen  
Stein wird im Hauptbereich angezeigt.

### 8.3 Scrollen = Zoom  
Graph bleibt stets glatt und flüssig.

### 8.4 Filter  
- nach Typ  
- nach Relevanz  
- nach Cluster  
- nach Quelle  

---

## 9. Systembau-UI

### 9.1 Baubereich ist immer leer beim Start
Nutzer muss bewusst Steine hineinziehen.

### 9.2 Verbindungen erscheinen als Linien
Linienfarbe = Kombinationsergebnis:
- grün: kompatibel  
- rot: Konflikt  
- gelb: unvollständig  

### 9.3 Sandbox-Tools rechts
- fehlende Steine  
- Optimierungen  
- Alternativen  

---

## 10. Zusammenfassung

Die Interface Logic stellt sicher, dass:
- alles verständlich ist  
- keine Hidden Features existieren  
- Nutzer aktiv entscheiden  
- Sandbox passiv unterstützt  
- HRM lernen kann  
- Graph sauber navigierbar bleibt  
- Konstruktion intuitiv möglich ist  

Das UI muss stets klar, logisch und technisch fokussiert bleiben.

