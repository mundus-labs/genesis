# MUNDUS LAB — Contribution Standards

Dieses Dokument definiert die Regeln und Standards für Beiträge zu MUNDUS.  
Nur wenn alle Mitwirkenden denselben Qualitätsanspruch einhalten,  
bleibt der Wissensgraph stabil, die Steinqualität hoch und das gesamte System verständlich.

Diese Regeln gelten für:
- neue Steine  
- Stein-Korrekturen  
- Beziehungen  
- Systemmodelle  
- Dokumentation  
- Erweiterungen  
- UI-/Sandbox-/HRM-bezogene Arbeiten  

---

# 1. Grundprinzipien für Beiträge

### 1.1 Klarheit ist oberstes Gebot  
Jeder Beitrag muss verständlich, präzise und eindeutig sein.

### 1.2 Ein Beitrag = ein klarer Zweck  
Keine vermischten Themen, keine unklaren Änderungen.

### 1.3 Qualität vor Menge  
Lieber ein sauberer Stein als zehn unklare.

### 1.4 Keine Spekulation  
Alles muss aus Dokumenten, Logik oder validiertem Wissen stammen.

### 1.5 Konsistenz  
Jeder Beitrag muss zum bestehenden System passen.

---

# 2. Standards für neue Steine

Ein neuer Stein muss:

1. **dem Steinformat entsprechen**  
2. **genau eine technische Aussage enthalten**  
3. **korrekt kategorisiert sein (MMF)**  
4. **eine eindeutige Summary besitzen**  
5. **requirements/results vollständig haben**  
6. **mindestens eine Quelle enthalten**  
7. **Version 1.0.0 setzen**  
8. **mindestens eine Beziehung besitzen**, falls logisch notwendig  

Steine, die gegen das Format verstoßen, werden abgelehnt.

---

# 3. Standards für Stein-Korrekturen

Eine Korrektur muss:

- klar formuliert sein  
- inhaltlich begründet sein  
- kategorisch korrekt sein  
- Beziehungen nicht zerstören  
- Version erhöhen (PATCH oder MINOR)  

Beispiel:
- Summary präzisiert → PATCH  
- category korrigiert → MINOR  
- relationship strukturell neu aufgebaut → MINOR  

---

# 4. Standards für Beziehungen

Eine Beziehung darf nur angelegt werden, wenn:

- sie logisch korrekt ist  
- sie durch den Inhalt der Steine begründet ist  
- sie einen der erlaubten Beziehungstypen benutzt  
- sie nicht redundant ist  
- sie nicht widersprüchlich ist  

Unerlaubt:
- multiple Bedeutungen  
- improvisierte Beziehungstypen  
- spekulative Ableitungen  

---

# 5. Standards für Systemmodelle

Systemmodelle müssen:

- nur validierte Steine verwenden  
- keine Roh-Steine erlauben  
- logisch geschlossene Funktionsketten bilden  
- Konflikte sichtbar machen  
- vollständig erklärbar sein  

Systeme mit Widersprüchen dürfen nicht als offizielle Beispiele gespeichert werden.

---

# 6. Standards für Dokumentationsbeiträge

Dokumentation muss:

- klar strukturiert  
- konsistent mit allen anderen Dateien  
- fehlerfrei formuliert  
- in der offiziellen Stilform geschrieben  
- frei von persönlichen Meinungen sein  

---

# 7. Standards für Erweiterungen (Extension Rules)

Neue Module, Tools oder UI-Komponenten müssen:

1. **deterministisch arbeiten**  
2. **den Kern nicht verletzen** (Steinformat, Graphregeln, HRM-Regeln)  
3. **austauschbar sein**  
4. **auditierbar sein**  
5. **keine spekulativen Ergebnisse liefern**  

Verboten:
- autonome Generierung von Wissen  
- Blackbox-Entscheidungen  
- Zerlegung ohne nachvollziehbare Logik  

---

# 8. Review-Prozess für Beiträge

1. Beitrag wird eingereicht  
2. automatischer Formatcheck  
3. menschlicher Review (Community oder Maintainer)  
4. bei Fehlern → Rückmeldung  
5. bei Zustimmung → Merge  
6. Graph wird aktualisiert  
7. HRM registriert den Beitrag als Signal  

Beitrag muss begründet sein:
- „Warum ist diese Änderung sinnvoll?“  
- „Welche Verbesserung schafft sie?“  

---

# 9. Ablehnungskriterien

Ein Beitrag wird abgelehnt, wenn:

- Steinformat verletzt wird  
- Kategorien falsch sind  
- Aussagen unklar sind  
- Beziehungen spekulativ sind  
- Logik gebrochen wird  
- Verifikation nicht möglich ist  
- der Ton oder Inhalt nicht sachlich ist  

---

# 10. Wartungsregeln

Mitwirkende müssen:

- veraltete Steine aktualisieren  
- Fehler im Graph melden oder korrigieren  
- Beziehungen stabil halten  
- Inkonsistenzen beheben  

HRM und Sandbox sind nur so gut wie die Korrekturen der Nutzer.

---

# 11. Ethik- und Qualitätskodex

Beiträge müssen:

- neutral sein  
- technisch korrekt  
- nachvollziehbar  
- dokumentiert  
- erklärbar  

Keine persönlichen Angriffe, kein Spam, keine Agenda.

---

# 12. Zusammenfassung

Die Contribution Standards garantieren:

- hohe Qualität  
- klare Struktur  
- verlässlichen Graph  
- präzise Steine  
- nachvollziehbares Wissen  
- langfristige Stabilität  

Sie sind verbindlich und bilden das Fundament einer globalen technischen Wissensplattform.

