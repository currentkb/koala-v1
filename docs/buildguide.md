# KOALA BUILD GUIDE

## PART LIST
| Part name       | Count | Remarks | 
| :-------------- | :---: | :------ |
| koala PCB       | 01 | You can find the files for it [here](/gerber/) |
| Pro Micro       | 01 |  |
| 12-Pin Sockets  | 02 |  |
| Mill-Max Pins   | 24 | optional |
| MX key switch   | 34 |  |
| MX hot-swap sockets   | 34 |  |
| diodes 1N4148W  | 34 | You can use surface mount or through hole diodes |
| 1u MX keycaps   | 34 | |
| USB cable       | 01 | For connecting the keyboard with your PC. USB-C or Micro-USB cable - depends on the pro micro you use |

## DIODES

The diodes needs to be soldered on the bottom of the PCB. Pay attention to their orientation:  They have a small line on one side, which should be on the side the arrow on the PCB is facing to.

![diodes](/docs/images/IMG_diodes.jpg)

## HOT-SWAP SOCKETS

The hot-swap sockets have to be soldered also on the bottom of the PCB.

![hot-swap](/docs/images/IMG_hot-swap.jpg)

## MCU

Solder the 12-pin sockets for the MCU.

![pin-sockets](/docs/images/IMG_back_mcu.jpg)

Turn around the PCB and solder the MCU onto the sockets. Make sure to solder the MCU top down. Optionally use Mill-Max pins to make the MCU swappable.

![mcu](/docs/images/IMG_top_mcu.jpg)

## CLEANING

You can use an old toothbrush and some isopropanol to clean it from residues.

## SWITCHES

Add your desired switches onto the board.

![switches](/docs/images/IMG_switches.jpg)

## FIRMWARE

If you have not already flashed the firmware to the microcontroller you should do it now.\
You can use the pre-built firmware for a [QWERTY layout](/firmware/koala_default.hex) or a [COLEMAK-DH layout](/firmware/koala_colemakdh.hex) or [modify and build your own QMK firmware](https://github.com/currentkb/qmk_firmware/tree/feat/koala/keyboards/koala).

After flashing the firmware, [make sure that every key is working](https://www.keyboardtester.com/).

## KEYCAPS

Finally, add some keycaps and happy typing.

![keycaps](/docs/images/IMG_keycaps.jpg)