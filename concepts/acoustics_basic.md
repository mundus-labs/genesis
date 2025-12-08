# Modul: Grundlegende Akustik (Acoustics)  
ID: acoustics_basic  
Kategorie: Physik / Wellen & Schwingungen  
Version: 1.0

## Funktion  
Analyse von Schallwellen, deren Ausbreitung, Wechselwirkung mit Materialien und Wahrnehmung.  
Grundlage für Mikrofone, Lautsprecher, Ultraschall-Sensoren und Vibrationsanalytik.

## Prinzip  
Schall ist eine mechanische Longitudinalwelle, die sich durch Druckschwankungen in einem Medium (Luft, Wasser, Festkörper) ausbreitet.

## Inputs  
- Schallquelle (Vibration)  
- Frequenz  
- Mediumeigenschaften  
- Amplitude  

## Outputs  
- Schalldruck  
- Lautstärke  
- Resonanz  
- Dämpfung  
- Frequenzspektrum  

## Grundgleichungen  

### Wellengeschwindigkeit  
c = √(K/ρ) (Medium-spezifisch)  
In Luft ca. 343 m/s bei 20°C.

### Schalldruckpegel  
L = 20 log₁₀(p/p₀) dB

### Wellenlänge  
λ = c / f  

### Impedanz  
Z = ρ × c

## Schallphänomene  
- Reflexion  
- Brechung  
- Beugung  
- Absorption  
- Interferenz  
- Resonanz  
- Dopplereffekt  

## Frequenzbereiche  
- Infraschall (< 20 Hz)  
- Hörbereich (20 Hz – 20 kHz)  
- Ultraschall (> 20 kHz)  
- Hyperschall (> 1 GHz)

## Abhängigkeiten  
- dynamics_basic  
- material_strength_basic  
- fluid_dynamics_basic  
- heat_transfer_basic  

## Mechanismus  
1. Schallquelle erzeugt periodische Druckschwankungen  
2. Wellenfront bewegt sich durch Medium  
3. Interaktion mit Oberflächen → Reflexion oder Absorption  
4. Empfänger (Ohr, Mikrofon, Sensor) wandelt Druck in Signal um  

## Kombinierbarkeit  
- Mikrofone & Lautsprecher  
- Ultraschallsensoren  
- Sonar  
- Materialprüfung (NDT)  
- Vibrationsanalyse  
- Akustikdämmung  
- Musikinstrumente  
- Robotik (Echolot, Entfernungsmessung)

## Beispiele  
- Lautsprecher erzeugt Schall  
- Ultraschall-Abstandssensor  
- Schalltomografie in Medizin  
- Raumakustik  
- Maschinenlärm-Analyse  

## Visualisierung (textuell)  
Schwingende Quelle → Druckwellen → Ausbreitung → Reflexion/Absorption → Detektion  

## Vorteile  
- extrem breites Anwendungsspektrum  
- hohe Präzision in Sensorik  
- nichtinvasive Messmethoden  

## Nachteile  
- stark mediumabhängig  
- Dämpfung über Distanz  
- Störungen durch Umgebungslärm  

## Quellen  
- Grundlagen der Akustik (Kinsler)  
- Physik der Schallwellen  
- Maschinenakustik & Vibrationslehre
