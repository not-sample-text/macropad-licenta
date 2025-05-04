# Firmware

Acest director conține codul sursă pentru microcontrolerul Raspberry Pi Pico.

Conținut:

- `src/` – Fișiere sursă pentru scanarea matricii de taste, afișajul OLED și encoderul rotativ
- `include/` – Fișiere header și configurații (ex: pinout, mapare taste)
- `lib/` – Librării externe (ex: driver pentru SSD1306)
- `CMakeLists.txt` – Configurația sistemului de build

Firmware-ul controlează logica tastaturii, funcționalitatea USB HID, afișajul OLED și interacțiunea cu intrările.
