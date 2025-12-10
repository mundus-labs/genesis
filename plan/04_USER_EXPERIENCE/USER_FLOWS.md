# MUNDUS LAB — User Flows

Dieses Dokument beschreibt die vollständigen Schritt-für-Schritt-Abläufe typischer Nutzeraktionen innerhalb von MUNDUS.  
User Flows definieren, wie Nutzer durch die Oberfläche navigieren und wie die Systemmodule miteinander interagieren.

Alle Flows folgen klaren, einfachen Abläufen und sind so gestaltet, dass Nutzer intuitiv arbeiten können.

---

## 1. Flow: Patent hochladen und zerlegen

1. Nutzer öffnet „Patent hochladen“.  
2. Datei wird eingelesen.  
3. Zerlegungssystem erzeugt Roh-Steine.  
4. Werkstatt zeigt Liste der Roh-Steine.  
5. Nutzer öffnet jeden Roh-Stein.  
6. Nutzer korrigiert Typ, summary, details.  
7. Nutzer überprüft Beziehungen.  
8. Nutzer speichert validierten Stein (Version 1.0.0).  
9. Stein wird in den Wissensgraph integriert.  
10. Graph aktualisiert Cluster und Kanten.  

Ergebnis: Das Patent ist vollständig in strukturierte Steine dekomponiert.

---

## 2. Flow: Steine vergleichen

1. Nutzer wählt mehrere Steine aus.  
2. Werkstatt öffnet Vergleichsansicht.  
3. Unterschiede werden hervorgehoben.  
4. Sandbox zeigt funktionale Alternativen.  
5. Nutzer entscheidet, welchen Stein er weiter nutzt.  

Ergebnis: Klarer Überblick über Unterschiede und Alternativen.

---

## 3. Flow: Steine kombinieren (Systemaufbau)

1. Nutzer öffnet Bauansicht.  
2. Nutzer zieht Stein A in den Arbeitsbereich.  
3. Nutzer zieht Stein B hinzu.  
4. Werkstatt prüft automatische Kompatibilität.  
5. Sandbox liefert Hinweise:
   - passt  
   - passt nicht  
   - hier fehlt ein Stein  
6. Nutzer fügt weitere Steine hinzu.  
7. Sandbox schlägt alternative Ketten vor.  
8. Nutzer finalisiert System.  

Ergebnis: Ein funktionales technisches System wird aus Steinen konstruiert.

---

## 4. Flow: Systemanalyse

1. Nutzer lädt ein existierendes System.  
2. Sandbox prüft alle Verbindungen.  
3. Konflikte werden markiert (rot).  
4. fehlende Steine werden angezeigt (gelb).  
5. alternative Mechanismen werden vorgeschlagen (blau).  
6. Nutzer wählt Lösung.  
7. System wird aktualisiert.  

Ergebnis: Fehler werden sichtbar und können korrigiert werden.

---

## 5. Flow: Graph erkunden

1. Nutzer öffnet Graphansicht.  
2. Knoten werden als Steine dargestellt.  
3. Beziehungen als Linien sichtbar.  
4. Nutzer zoomt in Cluster.  
5. Nutzer klickt einen Stein an → Detailansicht öffnet sich.  
6. Nutzer springt über Beziehungen zu verknüpften Steinen.  

Ergebnis: Nutzer erhält ein tiefes Verständnis über den technischen Raum.

---

## 6. Flow: Stein korrigieren

1. Nutzer öffnet einen Stein.  
2. klickt „Bearbeiten“.  
3. korrigiert Typ oder summary.  
4. ergänzt fehlende Felder.  
5. passt Beziehungen an.  
6. speichert Änderung → neue Version entsteht.  
7. HRM bekommt Lernsignal.  

Ergebnis: Stein wird präziser, Systemqualität steigt.

---

## 7. Flow: neuen Stein anlegen

1. Nutzer klickt „Neuer Stein“.  
2. wählt Kategorie.  
3. trägt Titel und summary ein.  
4. ergänzt Details, requirements, results.  
5. fügt Beziehungen hinzu.  
6. Quelle eingeben.  
7. Speichern → Version 1.0.0  
8. Stein erscheint im Graph.  

Ergebnis: Das Wissen im System wächst strukturiert.

---

## 8. Flow: Sandbox-Vorschlag prüfen

1. Nutzer konstruiert oder öffnet ein System.  
2. Sandbox zeigt Vorschläge:
   - fehlender Mechanismus  
   - alternative Lösung  
   - Optimierung  
   - Konflikthinweis  
3. Nutzer klickt Vorschlag an.  
4. Werkstatt zeigt Begründung und Pfade.  
5. Nutzer akzeptiert oder lehnt ab.  
6. HRM speichert Nutzerentscheidung als Lernsignal.  

Ergebnis: Vorschlagslogik verbessert sich, Systeme werden optimiert.

---

## 9. Flow: Optimierung durchführen

1. Nutzer öffnet System.  
2. klickt „Optimieren“.  
3. Sandbox analysiert:
   - kürzeste Funktionskette  
   - stabilste Mechanismen  
   - geringste Constraints  
   - mögliche Alternativen  
4. Sandbox zeigt Ranking der Varianten.  
5. Nutzer wählt Option.  
6. System aktualisiert sich.  

Ergebnis: technisch sinnvolle Optimierung eines Systems.

---

## 10. Flow: fehlerhafte Beziehungen bereinigen

1. Nutzer öffnet Graphansicht.  
2. falsch wirkende Beziehung wird markiert.  
3. Nutzer klickt „Beziehung bearbeiten“.  
4. Nutzer löscht oder ersetzt Beziehung.  
5. HRM registriert Muster.  

Ergebnis: Graph wird präziser und stabiler.

---

## 11. Flow: Wissenspflege (Quality Maintenance)

1. Werkstatt zeigt Liste unvollständiger oder veralteter Steine.  
2. Nutzer öffnet Stein 1.  
3. ergänzt fehlende Felder.  
4. aktualisiert Version.  
5. wiederholt für alle Steine.  

Ergebnis: Das System bleibt qualitativ sauber und zuverlässig.

---

## 12. Zusammenfassung

Die User Flows beschreiben klar und vollständig:

- wie Nutzer in MUNDUS arbeiten  
- wie Wissen transformiert wird  
- wie Systeme entstehen  
- wie Sandbox & HRM integriert sind  
- wie Qualität gepflegt wird  
- wie Navigation und Exploration funktionieren  

Sie bilden die Grundlage für UI-Design, Frontend-Architektur und Interaktionslogik.

