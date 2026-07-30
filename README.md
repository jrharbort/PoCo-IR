# PoCo-IR
This is a breakout board and ribbon to restore IR communication functionality to the Game Boy Pocket Color project by MouseBiteLabs, aka BucketMouse.

This project is still in development and may present design issues that are still being ironed out.

The breakout board PCB must be ordered in 1.2mm thickness and HASL finish, the flex ribbon is also required and can be ordered in standard 25µm thickness. Securing the ribbon may require the use of a lower melting point solder to prevent damage.

The flex ribbon is to be connected to CPU pins 44-51. It uses pins 44 and 49-51 as additional anchor points to hold the ribbon securely. These are ground pins and do not carry any voltage or data.

While there is sufficient clearance between the mainboard and cartridge slot metal shield for the mod to fit, it is recommended to cover this mod with tape to prevent any shorts in case a connection comes loose.

All components for the IR circuit must be salvaged from an original Game Boy Color (and you probably have it as a leftover from making a PoCo anyway).

The purple and black diodes will need their legs trimmed down before being soldered to the board. Keep track of which leg is longer and shorter and match them to the longer and shorter pads of the board to ensure correct orientation.
