# corne
Corne Keyboard Firmware

Pull this repo to ~/qmk-firmware/keyboards/crkbd/keymaps/<YOURNAME>

To update submodule: `git submodule sync —recursive && git submodule update --init —recursive`

Then: `qmk compile -kb crkbd/rev1 -km <YOURNAME> -e CONVERT_TO=helios`
