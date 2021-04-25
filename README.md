Device Tree for Redmi Note 9 (merlin)
==========================================

The Redmi Note 9 (codenamed _"merlin"_) is a high-end, mid-range smartphone from Xiaomi.
It was released in May 2020.

| Basic                   | Spec Sheet                                                                                                                     |
| -----------------------:|:------------------------------------------------------------------------------------------------------------------------------ |
| CPU                     | Octa-core                                                                                                                      |
| Chipset                 | Mediatek Helio G85                                                                                                             |
| GPU                     | Mali-G52 MC2                                                                                                                   |
| Memory                  | 3/4/6 GB RAM                                                                                                                   |
| Shipped Android Version | 10.0                                                                                                                           |
| Storage                 | 64/128 GB                                                                                                                      |
| Battery                 | Non-removable Li-Po 5020 mAh battery                                                                                           |
| Display                 | 1080 x 2340 pixels, 19.5:9 ratio (~395 ppi density)                                                                            |
| Camera (Back)(Main)     | 48 MP, f/1.8, 26mm (wide), 1/2.0", 0.8µm, PDAF                                                                                 |
| Camera (Front)          | 13 MP, f/2.3, 1.12µm                                                                                                           |

## Device picture
![merlin](https://cdn-files.kimovil.com/default/0004/60/thumb_359219_default_big.jpeg)

## Build instructions

```
# Compiling
$ export ALLOW_MISSING_DEPENDENCIES=true
$ . build/envsetup.sh
$ lunch omni_merlin-eng
$ make -jx recoveryimage //replace x in -jx with number of cores you want to allot for compilation

```
## Kernel source

You can find the kernel source used in this tree at [MiCode/Xiaomi_Kernel_OpenSource](https://github.com/MiCode/Xiaomi_Kernel_OpenSource/tree/lancelot-q-oss)

**Copyright 2021 The TWRP Open Source Project**
