# MacroPad-Workshop
macro pad design for the CFMG workshop
# ASSEMBLY STEPS

1. bend the legs of the diodes and put them into the holes labeled d(x) on the back of the pcb (the side with the logo). make sure the black stripe on the diode is pointing to the square hole
2. solder them in from the side where they are sticking out
3. cut the legs off the diodes
4. click the switches into the plate with the pins facing up
5. solder the pin headers that were included with the microcontroller on the back side of the board (side with logo), the short side of the headers go through the pcb.
6. click the switches and plate onto the board and then solder the switches.
7. solder the microcontroller onto the pin headers one pin above the bottom, this is due to an error in the library i used.

# FLASHING STEPS

1. install qmk toolbox
2. install the cmfg_macropad_default.hex file from this repo
3. select it in qmk toolbox
4. select auto flash
5. connect the macropad to your computer and then short the reset and ground pins using some metal thing
