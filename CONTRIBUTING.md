# MUNDUS LAB — CONTRIBUTING GUIDE

Danke, dass du zu MUNDUS LAB beitragen möchtest!  
Dieses Projekt lebt von präzisem Wissen, klaren Strukturen und gemeinsamer technischer Arbeit.  
Diese Anleitung erklärt, wie du korrekt beitragen kannst, ohne die Integrität des Systems zu gefährden.

---

# 1. Arten von Beiträgen

Du kannst beitragen, indem du:

- Roh-Steine aus Patenten/Papern extrahierst  
- Steine validierst (MMF-Konformität sicherstellen)  
- präzise Beziehungen zwischen Steinen einbringst  
- bestehende Steine verbesserst (summary, details, relations)  
- Lücken im Wissensgraph identifizierst  
- Research-Analysen erstellst  
- Dokumentation ergänzt  
- Fehler meldest oder Inkonsistenzen aufzeigst  

**Wichtig:**  
Sandbox erzeugt nichts — daher können keine „Sandbox-Kreationen“ eingereicht werden.

---

# 2. Repository-Struktur

- **concepts/**  
  Basiswissen, fundamentale technische Steine

- **research/**  
  Analysen, Zerlegungen, Patentstudien, Roh-Steine

- **meta/**  
  Systemdefinitionen, Steinformat, Graphregeln, Architektur

- **plan/**  
  Das vollständige Projekt-Framework (nur Maintainers bearbeiten)

Keine anderen Ordner dürfen ohne Zustimmung hinzugefügt werden.

---

# 3. Steine erstellen (MMF-Format)

Ein Stein folgt strikt dem offiziellen Steinformat:

- **title**  
- **type:** funktion | prinzip | mechanismus | input | output | constraint | dependency | combinability  
- **summary**  
- **details** (optional)  
- **requirements**  
- **results**  
- **relations** (nur erlaubte Typen)  
- **source**  
- **version**

**Roh-Steine:**  
Version `0.1.0`, unvalidiert, nicht graphfähig.

**Validierte Steine:**  
Version `1.0.0`, dürfen in den Graph.

---

# 4. Beziehungen hinzufügen

Erlaubte Beziehungstypen:

- **nutzt**  
- **basiert_auf**  
- **teil_von**  
- **alternative_zu**  
- **erweitert**  
- **ersetzt**  
- **verlangt**  
- **erzeugt**

Alle anderen Typen sind verboten.

Beziehungen müssen:

- logisch zwingend sein  
- eindeutig begründet werden  
- keine Kreise erzeugen  
- nicht spekulativ sein  

---

# 5. Workflow für Beiträge

1. Repository **forken**  
2. **Neuen Branch** anlegen  
3. Steine, Korrekturen oder Dokumentation hinzufügen  
4. Commit mit klarer Message  
5. Pull Request erstellen  
6. Review durch Maintainers  
7. Merge nach Zustimmung  
8. Steinversionen und CHANGELOG aktualisieren (falls relevant)

PR muss enthalten:

- Zweck der Änderung  
- klare Begründung  
- Quelle (wenn Stein)  
- Hinweis auf betroffene Dateien  

---

# 6. Qualitätsstandards

Beiträge müssen:

- technisch korrekt  
- klar und präzise  
- vollständig nachvollziehbar  
- neutral formuliert  
- quellenbelegt  
- im MUNDUS-Format geschrieben  
- frei von Spekulation sein

Nicht akzeptiert wird:

- Vermischung mehrerer Aussagen in einem Stein  
- erfundene Mechanismen oder Prinzipien  
- nicht erlaubte Beziehungstypen  
- falsche Kategorien  
- persönliche Meinungen oder Interpretationen  
- politischer oder ideologischer Inhalt  
- Patentverletzungen  
- Upload von geschützten Daten  

---

# 7. Was wir nicht akzeptieren

- Plagiate oder kopierte Patentinhalte  
- Upload von nicht lizenzierbarem Material  
- erfundene technische Inhalte  
- spekulative Funktionsannahmen  
- unzulässige Steinformate  
- Rückbau des Systems in Richtung „autonomer KI“  
- Missbrauch der Sandbox  
- Spam oder Werbung  
- Schädigende oder gefährliche Inhalte  
- Manipulation von HRM-Signalen  

---

# 8. Hilfe & Support

Du kannst jederzeit:

- Issues eröffnen  
- Fragen stellen  
- Diskussionen starten  
- Forschungsvorschläge einreichen  
- Inkonsistenzen melden  

Maintainers unterstützen dich beim korrekt mundus-konformen Arbeiten.

---

# TL;DR

**Steine, nicht Module.  
Keine Spekulation.  
Nur erlaubte Beziehungen.  
Fork → Branch → Änderung → PR → Review → Merge.  
Gemeinsam bauen wir ein präzises technisches Weltwissen.**

