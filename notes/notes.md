# GPS
## Navigation
Navigation hat Ursprung in Sehfahrt
### Seefahrt
Früher Orientierung an Sternen, Sextant -> Konzept: Abstandsbestimmung zu bekannten Punkten
### Längen und Breitengrade
Für Orte auf der Erde sind X,Y,Z-Kootdinaten unpraktisch (Erdkrümmung, 1 LE X ist nicht überall die gleiche Strecke)
Deshalb Einteilung in Längen-/Breitengrade und Höhe über NN.
## GPS-System
### Segmente
- Space Segment
- Control Segment
- User Segment
### Ein GPS-Satellit
- Atomuhr
- Antennen
- Nutzdaten
### Konstellation
- 24 Satelliten, deren Anordnung
- Nicht geostationär, sondern Umlaufzeit von 11h, 58 Minuten
- Ersatzsatelliten, Korrektur
### Das GPS-Signal
Verschiedene Bänder, Fokusierung auf C/A, L1 Band
#### Modulation
Einführung mit AM, dann kurzer Überblick BPSK
#### CDMA/PRN-Codes
Warum nötig? Überlagerung der Signale
Begrenzung der benötigten Bandbreite, Vergleich mit GLONASS
Auswitkungen auf Signalstärke
#### Nutzdaten
- Uhrzeit
- Allmanach
- Leichte Theorie (Paging, etc.)
### GPS-Empfänger
Schema (Antennen, etc.)
### GPS-Fix
#### Bestimmung der Laufzeit
Unterscheiden der Satelliten anhand von CDMA
Vergleichen der GPS-Codes, daraus errechnung der Laufzeit
#### Kalt/Warmstart
Dekodieren der Navigationsdaten
#### Bestimmen der Position
Gleichungssystem
Erklärung der Variablen
Evtl. Komplette Formeln (mit Längen und Breitengrad)
### Genauigkeit der Empfänger
Faktoren
- Athmosphäre
- Gebäude
#### Control Segment
Warum wird es gebraucht?
## Geschichte des GPS
NAVSTAR-Projekt
Abschaltung S/A
## GPS-Alternativen
- GLONASS
- Galileo
