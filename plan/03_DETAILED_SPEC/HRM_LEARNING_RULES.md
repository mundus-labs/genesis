# MUNDUS LAB — HRM Learning Rules

Das Human Reward Model (HRM) ist das lernende Modul von MUNDUS.  
Es verbessert kontinuierlich die Steinzerlegung, Vorschlagslogik der Sandbox, Graphstrukturen und Relevanzbewertungen.  
Dieses Dokument beschreibt die vollständigen Lernregeln, Signaltypen und Stabilitätsmechanismen.

---

## 1. Grundprinzip des Lernens

HRM lernt ausschließlich aus **echten Nutzerinteraktionen**.  
Es gibt:
- keine automatischen Selbstoptimierungen  
- keine autonomen Lernschritte  
- keine Modellfantasie  

Jedes Lernsignal stammt von menschlichen Entscheidungen.

---

## 2. Arten von Lernsignalen

HRM verarbeitet folgende Signale:

### 2.1 Korrektursignale
Entstehen, wenn der Nutzer:
- Kategorie eines Steins korrigiert  
- summary verbessert  
- details anpasst  
- constraints ergänzt  
- Beziehungen löscht oder hinzufügt  

→ HRM lernt Muster von typischen Fehlern und Korrekturen.

### 2.2 Annahme-/Ablehnungssignale
Wenn der Nutzer:
- Vorschlag der Sandbox annimmt (positiv)  
- Vorschlag verwirft (negativ)  

→ HRM verbessert Sandbox-Logik.

### 2.3 Konstruktionssignale
Wenn Nutzer erfolgreich:
- Systeme bauen  
- Mechanismen kombinieren  
- Funktionsketten schließen  
- Alternativen verwenden  

→ HRM erkennt stabile Muster.

### 2.4 Navigationssignale
Wenn Nutzer oft zwischen bestimmten Steinen wechselt:
- zeigt technische Relevanz  
- ergänzt Kontextgewichte  
- stärkt Graph-Pfade  

### 2.5 Frequenzsignale
Häufig genutzte Steine oder Kombinationen → höherer Relevanzwert.

---

## 3. Lernregeln

### 3.1 Kleine, kontrollierte Updates
HRM darf Wissen nicht verändern.  
Es verändert nur:
- Prioritäten  
- Gewichtungen  
- Vorschlagsreihenfolgen  
- Zerlegungsparameter  

### 3.2 Kein Überschreiben menschlicher Entscheidungen
HRM darf niemals:
- Nutzerentscheidungen korrigieren  
- Validierungen ändern  
- Beziehungen löschen  
- Steine neu kategorisieren  

### 3.3 Verstärkungsprinzip
Wenn Nutzer wiederholt:
- dieselben Korrekturen machen  
- dieselben Vorschläge annehmen  
- dieselben Alternativen nutzen  

→ HRM verstärkt diese Muster.

### 3.4 Abschwächungsprinzip
Wenn Nutzer:
- Vorschläge ablehnen  
- Alternativen ignorieren  
- Beziehungen löschen  

→ HRM schwächt Gewichtungen ab.

### 3.5 Konsistenzregel
HRM darf nur lernen, wenn:
- genug reale Signale existieren  
- Signale eindeutig sind  
- keine Widersprüche bestehen  

---

## 4. Lernbereiche des HRM

### 4.1 Zerlegungssystem (Decomposition Engine)
HRM verbessert:
- Satzmuster → Kategoriezuweisung  
- Trennregeln → Ein-Satz-Ein-Stein-Prinzip  
- Aufteilung komplexer Mechanismen  
- Extraktion von Constraints und Dependencies  

### 4.2 Sandbox
HRM verbessert:
- Ranking von Vorschlägen  
- Priorität kompatibler Steine  
- Alternativenlogik  
- Konflikterkennung  
- Optimierungsvorschläge  

### 4.3 Wissensgraph
HRM beeinflusst:
- Relevanz von Beziehungen  
- Pfadgewichtungen  
- alternativ bevorzugte Verbindungen  

### 4.4 Systempfade des Nutzers
HRM erkennt typische:
- Konstruktionen  
- Sequenzen  
- Lösungswege  
- Alternativpfade  

---

## 5. Stabilitätsmechanismen

### 5.1 Kein destruktives Lernen
HRM darf nie:
- Wissen entfernen  
- Wissen verändern  
- Graphstrukturen beschädigen  

### 5.2 Keine Blackbox
HRM muss erklärbare Entscheidungen treffen.

### 5.3 Keine spekulativen Regeln
Alles Lernen muss aus *respektierten menschlichen Signalen* stammen.

### 5.4 Versionierte Lernstände
HRM-Parameter dürfen versioniert werden:
- reproducibility  
- auditability  

### 5.5 Sicherheitsprüfung
HRM darf nur lernen, wenn:
- mindestens zwei konsistente Signale existieren  
- keine Regel verletzt wird  
- Beziehungen im Graph gültig bleiben  

---

## 6. Lernzyklen

Der Lernprozess läuft in klaren Zyklen:

1. Nutzer interagiert  
2. Signal wird erzeugt  
3. HRM interpretiert Signal  
4. HRM vergleicht mit bisherigen Mustern  
5. HRM aktualisiert Gewichtungen  
6. Sandbox/Zerlegung/Graph verwenden aktualisierte Werte  

Zyklus wiederholt sich endlos.

---

## 7. Zusammenfassung

HRM ist ein:
- kontrolliertes  
- erklärbares  
- nutzergetriebenes  
- deterministisches  
Lernsystem.

Es verbessert:
- Zerlegung  
- Vorschlagslogik  
- Graphstrukturen  
- Systemkonstruktion  

HRM ist der Teil von MUNDUS, der das System mit jeder Nutzung intelligenter macht.

