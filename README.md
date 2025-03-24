# Keyboard notes

## Details

This board was purchased in the 3rd round GroupBuy, which uses the V2 PCB.  

> V2 PCBs were only used in the 3rd GB round (R3). To confirm which version you need, remove the bottom from the keyboard and look beside the Corne-ish Zen logo for a version number. Group Buy rounds 1 and 2 have V1 PCBs and R3 has V2 PCBs. (Also V2 PCBs have white power switches... V1 PCBs have black ones.)

A lot of this repo is a fork from the main repo (as instructed) [here](https://github.com/LOWPROKB/zmk-config-Zen-2)


## Compiling
Firmware is compiled through a github action.  
You can find compiled firmware through the actions artifacts.

## flashing

Flash the firmware to your keyboard by double-clicking the reset button to put the it in bootloader mode. A window should pop up showing the contents of the storage on the keyboard. Drag and drop the correct .uf2 file into the window. When the upload is complete the window will close and the keyboard will exit bootloader mode.

 - If you only changed the keymap file you only need to flash the left side firmware to the left side.
 - If you changed the conf file you should flash both sides their respective files.

The keyboard is now ready to use.