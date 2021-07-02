# Nintendo
https://oshpark.com/shared_projects/a01xTNnj

## Purpose
These PCBs can be used to create cables that can be used on SNES, N64 and GameCube.

If you want to use the N64 make sure you have an RGB-modded one or you can only use CV (Composite-Video), as these boards do not support S-Video.

## Configurations
The configuraions all claim to be used with a direct wiring (e.g. with the VSAB-Plain)

### PAL-SNES
| Connection | Configuration |
| :-------------: | :-----: |
| SJ1/C4 | bridged |
| SJ3/C1| bridged |
| SJ4/C2| bridged |
| SJ5/C3| bridged |
| SJ2| either Luma or CV |
| R1| n.p. |
| R2| 75Ohm |
| R4| 75Ohm |
| R5| 75Ohm |
| R6| 75Ohm |

### NTSC-SNES
| Connection | Configuration |
| :-------------: | :-----: |
| SJ1/C4 | bridged |
| SJ3/C1| 220uF |
| SJ4/C2| 220uF |
| SJ5/C3| 220uF |
| SJ2| either Luma or CV |
| R1| n.p. |
| R2| n.p. |
| R4| n.p. |
| R5| n.p. |
| R6| n.p. |

### PAL-GameCube
| Connection | Configuration |
| :-------------: | :-----: |
| SJ1/C4 | 220uF |
| SJ3/C1| 220uF |
| SJ4/C2| 220uF |
| SJ5/C3| 220uF |
| SJ2| CV |
| R1| n.p. |
| R2| 75Ohm |
| R4| n.p. |
| R5| n.p. |
| R6| n.p. |

### N64
The N64 is different here. It depents on your mod which configuration you need.

E.g.: if you're using [borti4938](https://github.com/borti4938)s [N64Advanced](https://github.com/borti4938/n64rgb/tree/master/advancedRGBmod) Mod, you'd not place any part on the PCB at all:

| Connection | Configuration |
| :-------------: | :-----: |
| SJ1/C4 | bridged |
| SJ3/C1| bridged |
| SJ4/C2| bridged |
| SJ5/C3| bridged |
| SJ2| according to mod |
| R1| n.p. |
| R2| n.p. |
| R4| n.p. |
| R5| n.p. |
| R6| n.p. |