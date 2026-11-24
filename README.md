# ModuleConsommationCAMS-install

Page web d'installation du capteur de capacité ModuleConsommationCAMS
(LOLIN S2 Mini, ESP32-S2).

Page d'installation : <https://chrisdupuis.github.io/ModuleConsommationCAMS-install/>

Fonctionne dans Chrome ou Edge sur ordinateur, sous Windows et macOS, sans rien
installer.

| Fichier | Radio | Correction du courant |
|---|---|---|
| `CapacitySensor_Flysky100.bin` | FlySky (iBus) | aucune |
| `CapacitySensor_Futaba100.bin` | Futaba (SBUS2) | aucune |
| `CapacitySensor_Futaba118.bin` | Futaba (SBUS2) | ×1,18 |

Chaque fichier est une image complète, à flasher à l'adresse `0x0`.

Ce dépôt ne contient que la page d'installation et les firmwares compilés. Le
code source se trouve dans le dépôt privé `ModuleConsommationCAMS`, dont le
README explique comment les firmwares sont compilés et publiés ici.
