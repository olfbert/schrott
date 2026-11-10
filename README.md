# Schrottschleicher

Mehrspieler-Browserspiel: Schrott sammeln, an Robotern (rote Sichtkegel) und Drohnen (Scanner-Kreise) vorbeischleichen, alles am Ankauf verkaufen – wer am Ende das meiste Geld hat, gewinnt. Hinter Wänden verstecken, andere Spieler schubsen und am Ankauf Fähigkeiten kaufen (Unsichtbarkeit, Rauchwolke, Turbo, Muskelkraft).

- Eine einzige Datei: `index.html` (three.js und PeerJS kommen vom CDN)
- Mehrspieler per 4-stelligem Raumcode (PeerJS/WebRTC), am besten im selben WLAN
- Spielen: über GitHub Pages öffnen (Settings → Pages → Branch `main`)

Steuerung: Handy – links ziehen = laufen, Knöpfe rechts; PC – WASD, E = aufheben, F = schubsen, Q = ablegen, B = Laden, 1–3 = Fähigkeit, M = Karte, Mausrad = Zoom.

Karte: 80×80 m mit 8 Bereichen (Container-Terminal, Lagerhalle, Gerüst, Schrottplatz, Reifenlager, Werkstatt, Rohrlager, Fasslager) und oberer Etage über Rampen – je weiter draußen und je höher, desto wertvoller die Beute.

Einstellungen (`KONFIG`), Karte (`KARTE`) und eigene 3D-Modelle (`ASSETS`) stehen oben im Code.
