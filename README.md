# vrontakis_odinmini
Key mapping for kbdfans/odinmini custom firmware builds


Guide commands:

Setup qmk framework on your machine following this guide:
https://docs.qmk.fm/newbs_getting_started

On qmk terminal run:
qmk new-keymap -kb kbdfans/odinmini
Pick a name...

On qmk terminal run:
qmk compile -kb kbdfans/odinmini -km stvrontakis


Important Directories for QMK:
You will need to start compiling from the default library map of keyboard layout you are using. (for odinmini)
you are using C:/Users/<your-user>/qmk_firmware/keyboards/kbdfans/odinmini
And your custom keymap.c will be under /keymaps/<unique-name>

qmk will compile builds under C:/Users/<your-user>/qmk_firmware/.build (this is where the .uf2 file will end up
