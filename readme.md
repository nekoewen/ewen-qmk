This is a place for me to put my various QMK firmware profiles and compiled .hex files, plus a few .uf2 files for other types of keyboards. (It's weird that people hardly ever make the compiled firmware files available for download, right?)

The easiest way to flash firmware (that has already been compiled) is with the [QMK Toolbox](github.com/qmk/qmk_toolbox).

Install the Toolbox application, then open the .hex file. Check the "Auto-Flash" option, plug your controller in, and then when you bridge the GND and RST pins it should put the controller in bootloader mode and flash automatically.
