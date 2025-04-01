# Corne Firmware
Custom keymap for my Corne Rev3 with Helios microcontrollers
Simple 3-layer layout using Colemak-DH and numpad-style lower layer

Keymap `.json` designed [here](https://config.qmk.fm/#/crkbd/rev1/LAYOUT_split_3x6_3) and converted to `.c` [here](https://jhelvy.shinyapps.io/qmkjsonconverter/)

## To Compile:
- Install QMK  
- Clone this repo to `~/qmk-firmware/keyboards/crkbd/keymaps/<YOURNAME>`
- To update submodule: `git submodule sync —recursive && git submodule update --init —recursive`
- To compile: `qmk compile -kb crkbd/rev1 -km <YOURNAME> -e CONVERT_TO=helios`
This results in a firmware file at `~/qmk-firmware/<FIRMWARE>.uf2`

## To Upload:
- Unplug TRRS
- Open a graphical file manager (Nautilus, Dolphin, etc.)
- For each side:
  - Hold flash button
  - Plug in USB-C
  - Drag `<FIRMWARE>.uf2` file into flash memory
