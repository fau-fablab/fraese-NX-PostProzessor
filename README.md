# NX-PostProzessor
Ein NX PostProzessor für Eding-CNC 4-Achs Fräsen
Optimiert für die CNC-Fräse dess FAU-FabLab

# Achtung: Enthält Fehler
Der Aktuelle Stand ist noch größtenteils ungetestet;
Benutzung mit Vorsicht - Immer die 3D-Pfade der Maschienensteuerung Prüfen! <br>
Bekannte Fehler sind:
  - Bohrzyklus fährt *nicht* auf Sicherheitshöhe
  - G28 zu Beginn des Zyklus verursacht Kollisions-Warnung mit der Werkzeugtaster (Keepout-Area)

## Fehler und Probleme im NX
Hier eine Dokumentation bekannter Fehler des NX-CAM
  - S0: NX warnt nicht, wenn bei einem Werkzeug eine Spindel-RPM von 0 angegeben ist
  - Offenes Anfahren: Offene Anfahrwege (Ohne Rampe) immer Prüfen

