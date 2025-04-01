# corne
Custom keymap for the Corne Rev3 with Helios microcontrollers

#To use:

First install QMK  

Clone this repo to ~/qmk-firmware/keyboards/crkbd/keymaps/<YOURNAME>

To update submodule: `git submodule sync —recursive && git submodule update --init —recursive`

Then to compile: `qmk compile -kb crkbd/rev1 -km <YOURNAME> -e CONVERT_TO=helios`
