# MUNDUS LAB — Known Limitations

Dieses Dokument beschreibt die derzeit bekannten technischen, strukturellen und systemischen Einschränkungen von MUNDUS.  
Diese Limitierungen sind bewusst dokumentiert, um Fehlinterpretationen zu vermeiden und Entwicklungsprioritäten klar zu halten.

---

# 1. Limitierungen des Wissensgraphen

## 1.1 Nur validierte Steine sind erlaubt  
Roh-Steine können nicht im Graph genutzt werden.  
Dadurch entstehen Lücken, bis Nutzer die Steine validieren.

## 1.2 Beziehungen sind streng typisiert  
Es gibt nur eine kleine Anzahl erlaubter Beziehungstypen.  
Dies begrenzt Ausdruckskraft, verhindert aber Chaos.

## 1.3 Keine automatische Bedeutungsableitung  
Graph erkennt keine semantischen Ähnlichkeiten automatisch.  
Alles muss durch Nutzer, Sandboxlogik oder HRM entstehen.

## 1.4 Kein globales Rewriting  
Wenn ein Stein sich ändert, werden Beziehungen nicht automatisch neu berechnet.

---

# 2. Limitierungen der Zerlegung (Decomposition Engine)

## 2.1 Roh-Zerlegung ist nur syntaktisch  
System versteht Texte nicht inhaltlich – es extrahiert nur Strukturen.  
Logische Bedeutung muss durch Nutzer validiert werden.

## 2.2 Komplexe Mechanismen werden manchmal unvollständig getrennt  
Tiefe technische Passagen können zusammengesetzte Aussagen enthalten.

## 2.3 Kategorien-Vermutung ist fehleranfällig  
Nutzerkorrektur notwendig.

---

# 3. Limitierungen der Werkstatt

## 3.1 Begrenzte Darstellung großer Systeme  
Sehr große Systemmodelle können grafisch unübersichtlich werden.

## 3.2 Kein paralleles Editieren mehrerer Steine  
Nur ein Fokusobjekt zur Zeit.

## 3.3 Kein kooperatives Echtzeit-Editing  
Mehrere Nutzer können nicht gleichzeitig denselben Stein bearbeiten.

---

# 4. Limitierungen der Sandbox

## 4.1 Keine autonome Generierung  
Sandbox erzeugt keine neuen Steine oder Mechanismen.

## 4.2 Begrenzte Optimierungskomplexität  
MVM-Sandbox kann nur:
- Konflikte erkennen  
- Alternativen finden  
- minimal optimieren  

Keine tiefen Analysen.

## 4.3 Keine probabilistische Logik  
Sandbox kann nicht „wahrscheinlich“ entscheiden – nur logisch.

## 4.4 Keine automatische Erkennung versteckter Mechanismen  
Alles basiert auf bekannten Steinen.

---

# 5. Limitierungen des HRM

## 5.1 HRM lernt langsam und nur aus echten Nutzersignalen  
Kein künstliches Pretraining, kein automatisches Lernen.

## 5.2 HRM kann keine neuen Regeln erzeugen  
Es verstärkt nur vorhandene Muster.

## 5.3 Keine personalisierten Profile  
System kennt keine Nutzeridentitäten → anonymes Lernen.

## 5.4 HRM kann Wissensfehler nicht selbst korrigieren  
Nur Nutzer können Steine verbessern.

---

# 6. Limitierungen der UI

## 6.1 keine mobile volle Unterstützung (MVM)  
Komplexe Graphvisualisierung funktioniert mobil nur eingeschränkt.

## 6.2 kein Modus für extrem große Diagramme  
Frontend kann überlastet werden bei Systemen > 500 Knoten.

## 6.3 keine Simulation in der UI (bis später)  
Nur strukturelle Analyse, keine physikalischen Werte.

---

# 7. Limitierungen der Daten

## 7.1 Keine externen Datenbanken  
System nutzt nur vom Nutzer hochgeladene Inhalte.

## 7.2 Keine automatische Patentbeschaffung  
Nutzer müssen Patente selbst bereitstellen.

## 7.3 Keine Auto-Validierung  
System kann Wissensqualität nicht autonom sicherstellen.

---

# 8. Limitierungen der Erweiterbarkeit

## 8.1 Kernregeln dürfen nie geändert werden  
Kein neues Steinformat, keine neuen Beziehungstypen, keine autonomen Systeme.

## 8.2 Sandbox und HRM dürfen nicht „unterlaufen“ werden  
Plugins müssen strikt deterministisch bleiben.

---

# 9. Zusammenfassung

MUNDUS ist mächtig, aber absichtlich begrenzt:

- keine Autonomie  
- keine spekulativen Systeme  
- keine automatischen Bedeutungen  
- kein Selbstbau von Wissen  
- kein Overengineering  

Diese Limitierungen schützen Konsistenz, Klarheit und Stabilität  
und bilden die Grundlage für zukünftige Erweiterungen.

