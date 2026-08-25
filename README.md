# printhal-flasher

Öffentliche Web-Installer-Seite für PrintHAL. `index.html` ist von Hand
gepflegt; `bootloader.bin`, `partitions.bin`, `boot_app0.bin`,
`firmware.bin` und `manifest.json` werden automatisch von der GitHub
Action im privaten Source-Repo überschrieben, sobald dort auf `main`
gepusht wird — hier nichts davon von Hand bearbeiten, die Änderungen
gehen beim nächsten automatischen Build sonst wieder verloren.

Der aktuelle Platzhalter-`manifest.json` in diesem Ordner ist nur dafür
da, dass GitHub Pages von Anfang an eine gültige Seite ausliefert, bevor
die Action zum ersten Mal gelaufen ist.
