# cornehand

![cornehand](imgur.com image replace me!)

*A short description of the keyboard/project*

* Keyboard Maintainer: [Cameron Plimsoll](https://github.com/CameronPlimsoll)
* Hardware Supported: *The PCBs, controllers supported*
* Hardware Availability: *Links to where you can find this hardware*

Make example for this keyboard (after setting up your build environment):

    make cornehand:default

Flashing example for this keyboard:

    make cornehand:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available

![image](https://github.com/user-attachments/assets/7d12765a-a53a-4c95-b973-4b7b31947337)

![image](https://github.com/user-attachments/assets/84898d34-1e5d-4949-9c91-d73c59e853cd)

![image](https://github.com/user-attachments/assets/c28d5cd1-ded8-4ba5-a116-60b4b299c0e2)

