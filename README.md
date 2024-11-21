# ThanhSon.Mech PCB Collection

# E8ghty
![E8ghty](https://imgur.com/M4Oudco.png)
## Keymap
[Json](Via/trnthsn_8ghty_via.json)
## Firmware
[STM32F072](Firmware/E8ghty/F072/trnthsn_e8ghty_stm32f072_via.bin "download")
[STM32F103](Firmware/E8ghty/F103/trnthsn_e8ghty_stm32f103_via.uf2 "download")
# E8ghtyQK
# Mjolnir70
# S6xty
# S6xty Rev.2
# S6xtyMikeVuong
# S6xty5
# S6xty5 Rev.2
# S6xty5Neo
# S6xty5Neo Rev.2
# S7venty
# S7venty Rev.2

# S6xty5

![S6xty5](https://i.imgur.com/bFKBlnm.jpg)


A PCB for 65% keyboards. Uses a Left USB Type C connector or JST SH daughter board. 

![Layout](https://i.imgur.com/6gSoh0e.jpg)

* Keyboard Maintainer: [Trnthsn](https://github.com/trnthsn)
* Hardware Supported: STM32, S6xty5, Bakeneko65, Krush65
* Hardware Availability: [Trnthsn](https://www.facebook.com/ThanhSon.mech)

Make example for this keyboard (after setting up your build environment):

    make trnthsn/s6xty5:default

Flashing example for this keyboard:

    make trnthsn/s6xty5:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
