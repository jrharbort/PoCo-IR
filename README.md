# PoCo-IR
This is a breakout board and ribbon to restore IR communication functionality to the Game Boy Pocket Color project by MouseBiteLabs, aka BucketMouse.

This project is still in development and may present design issues that are still being ironed out.

The breakout board PCB must be ordered in 1.2mm thickness and HASL finish, the flex ribbon is also recommended and can be ordered in standard 25µm thickness. Securing the ribbon may require the use of a lower melting point solder to prevent damage.

The PCB is installed by soldering the 5V via to the 5V touchpoint on the PoCo board below the screen adjustment wheel, and the ground connects to the right side of the C40 capacitor. The flex ribbon is to be connected to CPU pins 44-51. It uses pins 44 and 49-51 as additional anchor points to hold the ribbon securely. These are ground pins and do not carry any voltage or data. Alternatively, if you have the right size wire and skills, you can run wires directly from the pads on the board to the respective CPU pins.

While there is sufficient clearance between the mainboard and cartridge slot metal shield for the mod to fit, it is recommended to cover this mod with tape to prevent any shorts in case a connection comes loose. I have also discovered that some aftermarket shells use a round headed screw to secure the cartridge slot shield, these will interfere with the position of the infrared diodes. It is recommended that the original flat screws are used as to not interfere with this mod.

All components for the IR circuit must be salvaged from an original Game Boy Color (and you probably have it as a leftover from making a PoCo anyway).

The purple and black diodes will need their legs trimmed down before being soldered to the board. Keep track of which leg is longer and shorter and match them to the longer and shorter pads of the board to ensure correct orientation.

## Example Installation
### Example with v1.0 revision
<img width="1216" height="955" alt="251206" src="https://github.com/user-attachments/assets/8354fe62-04af-451b-bd89-68a479e3c3e7" />

## PCB
### Front
<img width="2292" height="1247" alt="ir_v1-1-front" src="https://github.com/user-attachments/assets/7f10b786-c6f5-487d-a94b-6bbc7089dda9" />

### Back
<img width="2257" height="1222" alt="ir_v1-1-back" src="https://github.com/user-attachments/assets/ddb8439d-ea47-41b9-b889-b97ec58afd3d" />

## Ribbon
<img width="1825" height="1167" alt="ir_ribbon_v1-1" src="https://github.com/user-attachments/assets/48a54062-7ae7-4b7d-ac92-85e1458572c5" />

### Changelog
V1.1
- Further adjustments to PCB layout and shape. Made tweaks to ribbon to make fab creation and install easier.

V1.0
- Made tweak to PCB design. Created ribbon cable to connect board to CPU.

V0.9b
- Initial PCB design, needs manual connection to CPU with wires.
