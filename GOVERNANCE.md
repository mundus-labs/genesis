# MUNDUS LAB — GOVERNANCE

Dieses Dokument beschreibt die organisatorischen Grundstrukturen von MUNDUS.  
Ziel der Governance ist es, Offenheit, Transparenz, technische Integrität und langfristige Stabilität des Systems sicherzustellen.

Governance regelt:
- Rollen und Verantwortlichkeiten  
- Entscheidungsprozesse  
- Schutzmechanismen für das Kernsystem  
- Umgang mit Konflikten  
- Beiträge und deren Qualitätssicherung  

---

# 1. Grundprinzipien

Die Governance basiert auf folgenden fundamentalen Regeln:

- **Transparenz:** Entscheidungen, Diskussionen und Richtlinien sind offen einsehbar.  
- **Neutralität:** Keine politischen, ideologischen oder wirtschaftlichen Interessen.  
- **Technische Klarheit:** Entscheidungen müssen logisch und begründet sein.  
- **Offenheit:** Beiträge aller Personen sind willkommen, sofern sie den Standards entsprechen.  
- **Schutz des Kerns:** Steinformat, Graphregeln, Sandbox-Deterministik und HRM-Struktur sind unveränderlich ohne formelle Verfahren.

Diese Prinzipien entsprechen den Regeln in `CONTRIBUTION_STANDARDS.md` und `DECISION_RULES.md`.

---

# 2. Rollen im Projekt

## 2.1 Founder
- hat das Projekt initiiert  
- definiert die ursprüngliche Vision  
- bewahrt den historischen Zweck von MUNDUS  
- **keine Sonderrechte** über technische Entscheidungen

## 2.2 Core Maintainers
- pflegen die zentralen Repositories  
- prüfen Pull Requests  
- stellen Kompatibilität mit Kernregeln sicher  
- führen technische Reviews durch  
- dokumentieren Entscheidungen

## 2.3 Contributors
- erstellen Roh-Steine  
- validieren Steine  
- verbessern Dokumentation  
- melden Fehler oder Inkonsistenzen  
- schlagen Beziehungen oder Korrekturen vor

Contributors haben **gleiche Rechte bei technischen Vorschlägen**,  
sofern diese valide sind.

## 2.4 Reviewers
- prüfen Steinqualität  
- prüfen Beziehungen  
- sichern logische Konsistenz  
- bewerten technische Argumente  
- überwachen Regelkonformität

---

# 3. Entscheidungsprozesse

Alle Entscheidungen folgen strikt `DECISION_RULES.md`.

## 3.1 Kleine Entscheidungen
(z. B. Klarheitskorrekturen, Dokumentation, Roh-Steine)
- durch Maintainers per Review  
- kein Abstimmungsprozess

## 3.2 Mittlere Entscheidungen
(z. B. Änderungen an Beziehungen, Formatdetails, neue Werkstattfunktionen)
- Maintainer-Mehrheit genügt  
- Entscheidung dokumentieren

## 3.3 Große Entscheidungen
(z. B. Änderungen am Kern: Steinformat, Beziehungstypen, Graphstruktur)
- formelles Review  
- offene Diskussion  
- technische Begründungspflicht  
- dokumentierte Entscheidung  
- Maintainer-Konsens erforderlich

Wichtig:  
Keine Entscheidung darf **MMF**, **Graphregeln**, **Sandbox-Deterministik** oder **HRM-Struktur** verletzen  
ohne vollständigen MAJOR-Versionierungsprozess.

---

# 4. Schutz vor Machtkonzentration

- Keine Rolle darf unkontrolliert Entscheidungen treffen.  
- Maintainers müssen Entscheidungen dokumentieren.  
- Änderungen am Kern erfordern Konsens und öffentliche Transparenz.  
- Forks sind erlaubt, wenn Transparenz oder Regelkonformität verletzt wird.  
- Technische Argumente haben Vorrang vor persönlichen Meinungen.

**MUNDUS ist ein System, kein Besitz.**

---

# 5. Communityrechte

Jede Person darf:

- Vorschläge einreichen  
- Roh-Steine in Research erzeugen  
- Validierungen durchführen  
- Fehler melden  
- Diskussionen starten  
- auf Materialien im Repo zugreifen  

Die Community darf **nicht**:

- autonom neue Regeln definieren  
- Beziehungstypen erweitern  
- Kernformate ändern  
- spekulative Inhalte in den Graph einfügen  

---

# 6. Konfliktlösung

Konflikte werden rein technisch behandelt:

1. Problem offen benennen  
2. technische Argumente darstellen  
3. relevante Kernregeln prüfen  
4. Maintainers moderieren  
5. Entscheidung gemäß `DECISION_RULES.md` treffen  
6. Dokumentation im Governance-Ordner

Es gibt **keine persönlichen, sozialen oder politischen** Kriterien.  
Nur **Logik, Validität und Systemkompatibilität** entscheiden.

---

# 7. Weiterentwicklung der Governance

Governance kann angepasst werden, wenn:

- die Änderung transparent diskutiert wird  
- keine Kernregeln verletzt werden  
- die Änderung dokumentiert wird  
- Maintainer-Konsens vorliegt

Kernprinzipien bleiben unverändert, außer bei MAJOR-Version.

---

# TL;DR

- Founder = Ursprung, kein Machtzentrum  
- Maintainers = technische Stabilität  
- Contributors = Wissensträger  
- Entscheidungen = logisch und dokumentiert  
- Kernstrukturen sind geschützt  
- Community ist offen, aber regelgebunden  
- MUNDUS gehört der Technik, nicht Personen

