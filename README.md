# 🧮 FreeCAD Makro: Masse berechnen mit Dichte

Link: <https://wiki.freecad.org/Macro_at_Startup>

In diesem Projekt geht es darum, ein **eigenes FreeCAD-Makro** zu erstellen, das automatisch die **Masse eines 3D-Objekts** anhand des Volumens und einer einstellbaren Dichte berechnet.

## 🔧 Funktionen

- [x] Makro zur Masseberechnung basierend auf Volumen und Dichte (`wiege(1020)`)
- [x] Kompatibel mit Linux (getestet auf Arch und Debian) und Windows

## 📂 Aufbau

Die Makro-Dateien befinden sich im Verzeichnis: `~/.FreeCAD/Mod/macro\_startup/`

Dort befinden sich:

- `wiege.Py`: Das eigentliche Makro

## 🧪 Nutzung

1. FreeCAD öffnen
2. Makro - Makro ausführen
3. Modell mit Volumen auswählen
4. Python-Konsole öffnen
5. `wiege()` aufrufen – es wird automatisch die Masse berechnet


*Hinweis**: Die Dichte ist standardmäßig auf `2700` eingestellt, kann aber beim Funktionsaufruf angepasst werden: `wiege(7800)` z.B. für Stahl.

Falls kein Objekt ausgewählt ist, wird ein entsprechender Hinweis ausgegeben.

# 📹 Mein YouTube-Video

<https://youtu.be/CzCOK9WWYtc>

--

