# tabpad

![tabpad](imgur.com image replace me!)

*A short description of the keyboard/project*

* Keyboard Maintainer: [Pedro](https://github.com/Pedro-748)
* Hardware Supported: atmega32u4
* Hardware Availability: *Links to where you can find this hardware*

Make example for this keyboard (after setting up your build environment):

    make tabpad:default

Flashing example for this keyboard:

    make tabpad:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available

In QMK Toolbox use the "TabPad_Firmware_1.0.hex" File

