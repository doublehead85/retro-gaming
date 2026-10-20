# Retro-Konsole (GitHub Pages)

1. Repository auf GitHub anlegen und diese Dateien in das Hauptverzeichnis hochladen.
2. Unter Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save aktivieren.
3. Eigene, zur öffentlichen Bereitstellung berechtigte ROMs unter `roms/` und gegebenenfalls BIOS unter `bios/` hinzufügen.
4. In `games.js` die Demo-Einträge durch tatsächliche Spiele, Dateinamen und Kerne ersetzen.
5. Die GitHub-Pages-URL öffnen. EmulatorJS wird über das offizielle CDN geladen.

Achtung: Die enthaltenen Demo-Einträge sind Platzhalter. Es sind keine ROMs oder BIOS-Dateien enthalten. PS1-Dateiformat und BIOS müssen zur verwendeten EmulatorJS-Version passen. Cloud-Synchronisation von Spielständen ist nicht enthalten. ScummVM und DOS benötigen separate Web-Integrationen und sind in diesem Starter noch nicht spielbar.
