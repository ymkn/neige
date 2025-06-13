# Neige

Neige - A compact 30% keyboard with 3-rows and 12-columns row staggered layout in 12.75u width.

* Keyboard Maintainer: [ymkn](https://github.com/ymkn)

Make example for this keyboard (after setting up your build environment):

    make ymkn/neige:vial

Flashing example for this keyboard:

1. Enter the bootloader.
2. Simply copy ymkn_Neige_vial.uf2 to RPI_RP2 drive.

This keyboard supports [Vial](https://get.vial.today/) configurator.

## Bootloader

Enter the bootloader in 2 ways:

* **Bootmagic reset**: Hold down the key at (0,0) and (1,11) in the matrix (usually the top left key or Tab and the right 2nd top key or Enter) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the daughterboard
