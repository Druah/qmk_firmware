# efreet (as4x) Redux

![efreet](https://i.imgur.com/Kcw8HEh.png)
![PCB](https://i.imgur.com/jShRK6M.png)

A remake of a PCB for a Polish 40% keyboard with 19 mm switch grid spacing

* Keyboard Maintainer: [Druah](https://github.com/Druah)
* Hardware Supported: efreet Redux
* Hardware Availability: Private buy

Make example for this keyboard (after setting up your build environment):

    make druah/efreet_redux:default

Flashing example for this keyboard:

    make druah/efreet_redux:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (the top left key) and plug in the keyboard
* **Physical reset pads**: Briefly short the 2 pads circled and labelled with "RESET" on the back of the PCB
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
