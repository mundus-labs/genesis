# MUNDUS LAB — Decision Rules

Dieses Dokument definiert, wie Entscheidungen innerhalb des MUNDUS-Projekts getroffen werden.  
Es stellt sicher, dass alle Entscheidungen logisch begründet, transparent, stabil und projektkompatibel bleiben.  
Diese Regeln gelten unabhängig davon, wie groß das Projekt oder die Community wird.

---

# 1. Grundprinzipien der Entscheidungsfindung

### 1.1 Logik vor Meinung  
Jede Entscheidung muss technisch begründet sein – nicht politisch, nicht subjektiv.

### 1.2 Konsistenz vor Geschwindigkeit  
Es ist wichtiger, dass Entscheidungen das System nicht beschädigen, als dass sie schnell getroffen werden.

### 1.3 Der Kern ist unantastbar  
Zentrale Regeln (Steinformation, Graphbeziehungen, HRM-Grundregeln, Sandbox-Deterministik, Werkstattprinzipien) dürfen NIE verletzt werden.

### 1.4 Entscheidungen müssen nachvollziehbar sein  
Jede Entscheidung braucht eine Dokumentation der Gründe.

---

# 2. Entscheidungsarten

Es gibt drei Typen von Entscheidungen:

## 2.1 Technische Entscheidungen  
Betreffen:
- Steinformat  
- Graphregeln  
- Sandboxlogik  
- HRM-Lernen  
- Zerlegungssystem  
- Architektur  

Diese Entscheidungen benötigen strenge Logikprüfung.

## 2.2 UI-/Interaktionsentscheidungen  
Betreffen:
- Layout  
- Nutzerfluss  
- Werkstattfunktionen  
- Visualisierungen  

Diese Entscheidungen berücksichtigen:
- Nutzbarkeit  
- Klarheit  
- kognitive Last  

## 2.3 Projekt-/Organisationsentscheidungen  
Betreffen:
- Roadmap  
- Versionierung  
- Erweiterungen  
- Community-Regeln  

---

# 3. Entscheidungsprozess

Jede Entscheidung durchläuft folgende Schritte:

1. **Problem beschreiben**  
2. **Optionen sammeln**  
3. **Kernregeln prüfen**  
4. **Konflikte erkennen**  
5. **Begründung formulieren**  
6. **Entscheidung treffen**  
7. **Dokumentation aktualisieren**  
8. **Implementierung freigeben**  

Keine Kurzschlüsse, keine spontanen Richtungswechsel.

---

# 4. Prüfregeln vor jeder Entscheidung

Eine Entscheidung ist nur gültig, wenn die Antwort auf alle folgenden Fragen **JA** ist:

### 4.1 Unterstützt die Entscheidung das Ziel von MUNDUS?  
(→ technische Klarheit, Struktur, Kombinierbarkeit)

### 4.2 Bleibt der Kern unbeschädigt?  
(→ kein neues Steinformat, keine neuen Beziehungstypen, keine Spekulation)

### 4.3 Ist die Entscheidung logisch begründbar?  
(→ ergibt sich aus Systemlogik oder Nutzerverhalten)

### 4.4 Ist die Entscheidung langfristig stabil?  
(→ führt nicht später zu inkonsistenter Entwicklung)

### 4.5 Ist die Entscheidung reversibel?  
(→ notfalls zurücksetzbar)

Wenn **eine Antwort nein ist → Entscheidung wird verworfen.**

---

# 5. Konfliktlösungsregeln

Wenn mehrere Lösungen möglich sind:

### 5.1 Lösung mit geringster Systemkomplexität gewinnt  
Einfacher ist stabiler.

### 5.2 Lösung, die mehr Klarheit erzeugt, gewinnt  
Schwierige Systeme verlieren.

### 5.3 Lösung, die schwerer missbraucht werden kann, gewinnt  
Robustheit schützt das Projekt.

### 5.4 Lösung, die weniger Spezialfälle benötigt, gewinnt  
Generalität geht vor Sonderlogik.

### 5.5 Lösung, die besser dokumentierbar ist, gewinnt  
Nachvollziehbarkeit ist Pflicht.

---

# 6. Entscheidungskompetenz

### 6.1 Der Steinformat-Kern  
Darf nur angepasst werden durch:
- Projektleitung  
- technische Maintainer  
- formelle Abstimmungsphase  

### 6.2 Graphregeln  
Dürfen von Maintainers angepasst werden.  
Community darf Vorschläge machen, aber nicht direkt ändern.

### 6.3 Sandboxregeln  
Sandboxentwicklung ist hochsensibel.  
Änderungen müssen vollständig geprüft und dokumentiert werden.

### 6.4 HRM-Regeln  
Nur minimal änderbar, wegen langfristigen Lernverhaltens.

### 6.5 UI-Entscheidungen  
Können flexibel angepasst werden, solange Logik erhalten bleibt.

---

# 7. Entscheidungsdokumentation

Jede Entscheidung muss dokumentiert werden:

- Was wurde entschieden?  
- Warum wurde es entschieden?  
- Welche Optionen gab es?  
- Welche Regeln waren relevant?  
- Welche langfristigen Effekte hat das?  

Die Dokumentation muss im Ordner **/governance/decisions/** gespeichert werden  
(kann später im Repo entstehen).

---

# 8. Schutzregeln gegen Chaos

### 8.1 Keine spontanen Richtungswechsel  
Große Entscheidungen benötigen Prüfzeit.

### 8.2 Keine widersprüchlichen Module  
Alles muss kompatibel bleiben.

### 8.3 Keine unabhängigen Wissensinseln  
Nur ein Graph, ein Format, ein Regelset.

### 8.4 Keine persönliche Meinung als Argument  
Nur technische Begründungen zählen.

---

# 9. Zusammenfassung

Die Decision Rules stellen sicher:

- Stabilität  
- Konsistenz  
- Klarheit  
- langfristige Entwicklungsfähigkeit  
- Schutz des Kerns  
- Transparenz für alle Mitwirkenden  

Ohne diese Regeln würde das Projekt chaotisch, inkonsistent oder unbrauchbar werden.  
Mit diesen Regeln bleibt MUNDUS auf Kurs — egal wie groß es wird.

