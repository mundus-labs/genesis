# MUNDUS LAB — Projektumfang (SCOPE)

## 1. Definition des Projektumfangs
Der Umfang von MUNDUS LAB beschreibt alle Bereiche, Funktionen und Strukturen,
die das System umfasst. Der Scope legt fest, was Bestandteil der Plattform ist,
welche Aufgaben sie erfüllt und welche Kernmechanismen sie bereitstellt.

MUNDUS ist ein System zur:
- Zerlegung technischer Informationen in Bausteine,
- Speicherung dieser Bausteine in einem Wissensgraph,
- Korrektur und Verfeinerung durch Nutzer,
- Nutzung der Bausteine für Analyse, Vergleich, Simulation und Entwicklung,
- Erzeugung neuer technischer Lösungen aus bestehenden Bausteinen.

Alles, was zu diesen zentralen Aufgaben gehört, liegt **innerhalb** des Scopes.

---

## 2. Hauptkomponenten innerhalb des Scopes

### 2.1 Wissensbausteine („Steine“)
- Strukturierte atomare Einheiten technischen Wissens  
- Standardisiertes Format gemäß MMF  
- Entstehung durch automatische Zerlegung und Nutzerkorrektur  
- Speicherung im Wissensgraph

### 2.2 Wissensgraph
- Verknüpfung aller Bausteine  
- Darstellung von funktionalen, mechanischen und logischen Beziehungen  
- Grundlage für Navigation, Analyse, Suche und Kombination  
- Dynamisch erweiterbar durch Nutzerinteraktion

### 2.3 Werkstatt
- Nutzeroberfläche für die praktische Arbeit mit Bausteinen  
- Analyse, Vergleich, Zerlegung, Kombination  
- Konstruktion eigener Technologien  
- Exploration von Alternativen und Varianten

### 2.4 Sandbox
- Ausführungsmodul, das Bausteine logisch kombiniert  
- Nutzung von Regeln, Constraints und Beziehungen  
- Vorschläge für Optimierungen und neue Lösungen  
- Simulationsunterstützung (vereinfacht, nicht vollphysikalisch)

### 2.5 HRM (Human Reward Model)
- Lernsystem basiert auf realer Nutzung  
- Verbessert automatische Zerlegung  
- Verbessert Vorschläge der Sandbox  
- Passt sich an Bedürfnisse der Nutzer an  
- Keine externen Datensätze, kein Black-Box-Training

### 2.6 Automatisierte Zerlegung technischer Dokumente
- Patente  
- wissenschaftliche Texte  
- Funktionsbeschreibungen  
- technische Spezifikationen  
- Baupläne  
- Module aus concepts/

Ziel: Roh-Bausteine erzeugen, die Nutzer verfeinern.

### 2.7 Nutzerinteraktion
- Korrekturen  
- Einordnungen  
- Bausteinverbesserungen  
- Validierungen  
- Kombinationen  
- Entscheidungen in der Werkstatt

Die Nutzerinteraktion ist essenzieller Bestandteil des Systems.

---

## 3. Technologischer Umfang

### 3.1 Daten
Innerhalb des Scopes:
- Text  
- strukturierte Bausteine  
- Beziehungen  
- einfache Parameter  
- technische Beschreibungen  

Nicht innerhalb des Scopes:
- vollständige CAD-Dateien  
- vollständige Simulationen realer Physik  
- GPU-basierte Hochleistungsmodelle  
- Big-Data-Langzeitarchive

(Details in NON_GOALS.md)

---

## 4. Funktionaler Umfang

Innerhalb des Umfangs:
- Zerlegen
- Verknüpfen
- Ordnen
- Kombinieren
- Vergleichen
- Optimieren (vereinfacht)
- Erklären
- Vorschlagen

Nicht innerhalb:
- Vollautomatisches Erfinden ohne Nutzer  
- Marktanalysen  
- Patentprüfungen im juristischen Sinn  
- Realwelt-Produktion

---

## 5. Erweiterbarkeit
Der Scope ist so definiert, dass:

- jede Neuerung ein Baustein ist,
- jede Funktion in die bestehende Struktur eingebettet werden kann,
- keine Grundlogik verletzt wird.

Alle Module dürfen wachsen —  
der **Kernumfang bleibt stabil**.

---

## 6. Verbindung zu NON_GOALS.md
Der Scope wird nach unten durch klare Ausschlüsse begrenzt.
Diese befinden sich in der Datei `NON_GOALS.md`.

---

## 7. Zusammenfassung
Der Scope definiert MUNDUS als:

> *Ein modulares technisches Wissenssystem, das Wissen zerlegt,
>  ordnet, kombiniert und zur Entwicklung neuer Ideen nutzbar macht.*

Alles, was diesem Zweck dient, ist Teil des Systems.

