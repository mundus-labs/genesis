# Modul: Grundlegende Design-Constraints (Design Constraints Fundamentals)  
ID: design_constraints_basic  
Kategorie: Systemtechnik / Einschränkungen & technische Grenzen  
Version: 1.0

## Funktion  
Definiert alle technischen, physikalischen und sicherheitsrelevanten Grenzen, die die Sandbox bei der Systemgenerierung berücksichtigen muss.  
Design-Constraints verhindern unrealistische, unsichere oder nicht fertigbare Systeme und dienen als Leitplanken für die KI.

## Prinzip  
Constraints beschränken den Suchraum der KI auf realisierbare Lösungen.  
Sie wirken als Filter, Regeln, Grenzwerte und Anforderungen, die jedes Modul und jedes System erfüllen muss.

## Inputs  
- Materialdaten  
- physikalische Gesetze  
- Schnittstellenparameter  
- Fertigungsgrenzen  
- Sicherheitsregeln  
- Leistungsanforderungen  
- externe Normen (vereinfacht)  

## Outputs  
- gültige Parameterbereiche  
- Ausschlusskriterien  
- Fehlermeldungen  
- Optimierungsgrenzen  
- Constraints für Simulation & Inferenz  

## Constraint-Typen  

### 1. Physikalische Constraints  
- Energieerhaltung  
- maximale Kräfte / Momente  
- maximale Ströme / Spannungen  
- Temperaturgrenzen  
- Druckgrenzen  
- Stabilität & Resonanz  
- maximale Geschwindigkeit / Beschleunigung  

### 2. Material-Constraints  
- Elastizität  
- Zugfestigkeit  
- Wärmeleitfähigkeit  
- elektrische Leitfähigkeit  
- Korrosionsbeständigkeit  
- thermische Ausdehnung  

### 3. Fertigungs-Constraints  
- minimale Wandstärken  
- Bohrungsgrößen  
- Toleranzen  
- Werkzeugzugänglichkeit  
- maximale Bauteilgröße  
- Montagefreundlichkeit  

### 4. Schnittstellen-Constraints  
- elektrische Kompatibilität  
- mechanische Passform  
- Protokollkompatibilität  
- Energieflussgrenzen  

### 5. Sicherheits-Constraints  
- Überlastschutz  
- thermische Sicherheit  
- Abstandsnormen  
- Fail-Safe Anforderungen  
- Druck- & Explosionsschutz  

### 6. Ethik- und HRM-Constraints  
- kein übermäßiger Ressourcenverbrauch  
- verständliche Systemarchitektur  
- minimierter Schaden  
- nachhaltige Materialwahl  

### 7. Betriebs-Constraints  
- Umgebungstemperatur  
- Feuchtigkeit  
- Erschütterungen  
- chemische Belastung  

## Abhängigkeiten  
- safety_basic  
- ethics_basic  
- interface_definition_basic  
- system_design_basic  
- manufacturing_basic  
- simulation_engine_basic  
- optimization_basic  

## Mechanismus  
1. Sandbox lädt Anforderungen  
2. Constraints definieren gültigen Parameterraum  
3. KI generiert Entwurf  
4. Constraints prüfen Entwurf:  
   - Werte in Range?  
   - Schnittstellen korrekt?  
   - Material geeignet?  
   - Fertigung möglich?  
   - Sicherheit erfüllt?  
5. Ungültige Designs werden verworfen  
6. Optimierung nutzt Constraints als Grenzen  
7. finale Systeme sind garantiert realistisch  

## Kombinierbarkeit  
- Systemdesign  
- Simulation  
- Optimierung  
- Sicherheitsanalyse  
- Fertigung  
- Variantenbildung  
- Reverse Engineering  

## Beispiele  
- Motorstrom > zulässiger ESC-Strom → ungültig  
- Material schmilzt bei Betriebswärme → ungültig  
- Sensor benötigt 3.3V, System liefert 5V → Warnung  
- Wandstärke < 1 mm → Fertigung ungeeignet  
- Getriebeübersetzung instabil → Simulation schlägt Alarm  

## Visualisierung (textuell)  
Anforderung → Constraints → KI-Entwurf → Prüfung → OK / Fehler → neues Design  

## Vorteile  
- verhindert unrealistische Designs  
- erhöht Systemsicherheit  
- reduziert Ausfallrisiken  
- beschleunigt Synthese  
- erleichtert Optimierung  
- verbindet Physik und KI  

## Nachteile  
- zu strenge Constraints können Innovation hemmen  
- zu lockere Constraints lassen fehlerhafte Systeme zu  
- erfordert kontinuierliche Pflege  

## Quellen  
- technische Normen (ISO, DIN, IEC)  
- Ingenieurhandbücher  
- Design for Manufacturing (DFM)  
- Systems Engineering Guidelines
