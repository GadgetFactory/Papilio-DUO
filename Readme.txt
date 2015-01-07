BPC3012 Papilio DUO Manufacturing Package - Current Version 1.6

Special assembly instructions:
	-Use RED for the PCB color and white for the silkscreen color.

Test Plan Home Page:
	- http://www.gadgetfactory.net/opmanuals/index.php?n=Main.PapilioDUO

CHANGELOG
1/7/2015 V1.6
	-Made the through holes for mounting on the micro-usb via's instead of holes so they can be soldered.
	-Removed Kickstarter edition
	-Fixed angles on some of the traces
	-PCB color is RED now.

9/30/2014 V1.5 - Kickstarter Edition
	-Added TQFP footprint for the ATmega32U4
	-Changed values for LED resistors so they won't be so bright. R7, R29, R30
	-Changed size of the EEPROM used by the FT2232H chip from 1K to 2K. This allows us to look like official Xilinx Cable. U3
	-Fixed up some silkscreen markings to make it more obvious how to place the parts.
	-Added the Kickstarter Special Edition Marking
	-Changed PCB color to Black

7/30/2014 V1.4
	-Added getting started URL
	-Fixed full silkscreen	

6/4/2014 V1.4
	-Fixed the mounting holes
	-Removed original Arduino mounting holes

4/16/2014 V1.3
	-VBUS connected
	-RX/TX LED's changed to port B
	-Silkscreen changes
	-HDMI removed

3/5/2014 V1.2
	-Shrunk the board to 100cm in order to better fit Chinese standards and save money in manufacturing.

3/5/2014 V1.1
	-Fixed problems for manufacturability (thanks to Mitch at Hackvana)
		-Fixed clearance problem on FPGA pins 144 and 36
		-Moved trace between FT2232H pins 10 and 11 to inside of part so it does not look like a solder bridge up on inspection.
		-Fixed Silkscreen size for the 22-53 numbering
		-Updated the CC-BY-SA text to indicate license number CC-BY-SA 4.0

3/3/2014 V1.0
	Initial Release