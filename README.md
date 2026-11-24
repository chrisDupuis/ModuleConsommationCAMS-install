# ModuleConsommationCAMS-install

Web installer for the ModuleConsommationCAMS capacity sensor (LOLIN S2 Mini,
ESP32-S2).

Installer page: <https://chrisdupuis.github.io/ModuleConsommationCAMS-install/>

Works in Chrome or Edge on a computer, on Windows and macOS, with nothing to
install.

| File | Radio | Current correction |
|---|---|---|
| `CapacitySensor_Flysky100.bin` | FlySky (iBus) | none |
| `CapacitySensor_Futaba100.bin` | Futaba / FrSky (SBUS2) | none |
| `CapacitySensor_Futaba118.bin` | Futaba / FrSky (SBUS2) | x1.18 |

Each file is a complete image flashed at address `0x0`.

This repository only holds the installer page and the prebuilt firmwares. The
source code lives in the private repository `ModuleConsommationCAMS`, whose
README explains how the firmwares are built and published here.
