# neige

neige - A compact 30% keyboard with 3-rows and 12-columns row staggered layout in 12.75u width.

* Keyboard Maintainer: [ymkn](https://github.com/ymkn)

Make example for this keyboard (after setting up your build environment):

    make ymkn/neige:vial

Flashing example for this keyboard:

1. Install and open [QMK Toolbox](https://qmk.fm/toolbox).
2. Disconnect the keyboard from the computer.
3. Hold the top-left key while connecting the USB cable, or hold the BOOT button on the back of the PCB while connecting the USB cable.
4. Confirm that QMK Toolbox shows `STM32 DFU device connected (WinUSB): STMicroelectronics STM32 BOOTLOADER`.
5. Click `Open` and select the compiled firmware file.
6. Click `Flash` and wait for the process to finish.
7. When QMK Toolbox shows `Flash complete`, the firmware update is complete.

This keyboard supports [Vial](https://get.vial.today/) configurator.

## Bootloader

Enter the bootloader in 2 ways:

* **Key on plug-in**: Hold the top-left key while connecting the keyboard to USB.
* **BOOT button**: Hold the BOOT button on the back of the PCB while connecting the keyboard to USB.
