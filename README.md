# COLORado PXL Bar 8

## Software Versions

[V1.241023 - COLORado PXL Bar 8](https://github.com/Chauvet-Pro/COLORADOPXLBAR8/blob/5905e87eaa4b8ed54082b55b718fc67e3f87fa4c/FIRMWARE/V1.241023.zip)
- Fixed control-channel values

[V1.240807 - COLORado PXL Bar 8](https://github.com/Chauvet-Pro/COLORADOPXLBAR8/blob/54f512eb1b25fcddd209a251afc71c81b875509b/FIRMWARE/V1.240807.zip)
- Added new PWM firmware update

[V1.240719 - COLORado PXL Bar 8](https://github.com/Chauvet-Pro/COLORADOPXLBAR8/blob/a0feeceb9c92af3a0c12a8a8d2899c4e421d344f/FIRMWARE/V1.240719.zip)
- Fixed the thermistor error issue

[V1.240219 – COLORado PXL Bar 8](https://github.com/Chauvet-Pro/COLORADOPXLBAR8/blob/df907d5822307a832c1fc9611a6ab5c992eccc2a/FIRMWARE/V1.240219.zip)
-	Fixed IGMP subscription issue

[V1.230321 – COLORado PXL Bar 8](https://github.com/Chauvet-Pro/COLORADOPXLBAR8/blob/df907d5822307a832c1fc9611a6ab5c992eccc2a/FIRMWARE/V1.230321.zip)
-	Fixed dimming issues and spelling errors

[V1.221102 – COLORado PXL Bar 8](https://github.com/Chauvet-Pro/COLORADOPXLBAR8/blob/df907d5822307a832c1fc9611a6ab5c992eccc2a/FIRMWARE/V1.221102.zip)
-	Added the ability to disable tilt from the menu.
•	Customer can turn the fixture on then set the tilt to off position in the menu. As soon as this function is activated, the tilt will be turned off until it is turned back on from the display.
-	Added the ability to change the start LED from left to right (from the menu and DMX)
-	Added PWM settings to the control channel
-	Added HTP color preset function similar to the Rogue and Maverick Beam Wash fixtures

[V1.220627 – COLORado PXL Bar 8](https://github.com/Chauvet-Pro/COLORADOPXLBAR8/blob/df907d5822307a832c1fc9611a6ab5c992eccc2a/FIRMWARE/V1.220627.zip)
-	Fixed issues with Red Shift and Web server display message

[V1.211112 – COLORado PXL Bar 8](https://github.com/Chauvet-Pro/COLORADOPXLBAR8/blob/df907d5822307a832c1fc9611a6ab5c992eccc2a/FIRMWARE/V1.211112.zip)
-	Improved the sensitivity for temperature changes for better control

&nbsp;

## USB Software Update Instructions
1. Power on the product and plug the flash drive into the USB port.
2.	Once the flash drive has been detected, the message "**USB UPDATE**" will be displayed. Select **YES**.  
3.	The next screen will show the software versions available for this fixture on the USB drive.  For multiple versions of the software for the same fixture, use **UP** or **DOWN** to select the desired version.  Press **ENTER**.
4.	The “**USB UPDATE**” screen will re-appear.  Press **YES**.
5.	The upgrade will start. **DO NOT** turn off the power or disconnect the USB while the USB LED is still blinking during the process. The screen display will read: “**USB Update Wait**”. USB update can take several minutes to complete.
   >When the USB firmware is done uploading, in some fixtures the display will change to: “**DO NOT UNPLUG, UPDATING**”.
6.	When the update is completed, the fixture will automatically reboot.
7.	Go to Fixture Information on the product’s menu map and confirm the firmware revision.
8.	When the boot-up process is finished, restart the product.

### Special Notes
* Place the .chl file in the root directory of the USB drive.
* The product's USB port supports up to 32GB capacity and only works with FAT32 file format.
* Turning off the power or removing the USB while still blinking during the update will cause partial or total firmware failure in the targeted fixture(s). If this occurs, the user will need the UPLOAD 08 device to fix this.
