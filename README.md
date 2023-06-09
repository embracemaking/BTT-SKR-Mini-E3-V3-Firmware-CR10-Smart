# BTT-SKR-Mini-E3-V3-Firmware-CR10-Smart
Repository for BTT SKR Mini E3 V3 firmware for the CR10 Smart mainboard upgrade made easy using the Embrace Making 'Easy Swap PCB kit' which can be found here:

* https://embracemaking.com/products/cr10-smart-cr6-se-mainboard-easy-swap-pcb-kit

Print head parts for the CR10 Smart to enable mounting of the CR Touch module:

* https://embracemaking.com/products/creality-cr10-smart-cr-touch-lgx-lite-5015-cooling-fan-conversion

Video showing the entire installation of all upgrades and mainboard on a CR10 Smart:

* https://youtu.be/vo5xYLcvk2w

Pre-compiled .bin file accomodates the following modifications:

* BTT TFT35 V3 touchscreen
* CR-touch ABL sensor
* LGX Lite direct drive extruder
* BTT Relay V1.2.
* Neopixel Jewel RGBW https://www.adafruit.com/product/2860
* 100kohm thermistor
* Creality filament runout sensor

Wiring diagrams here:

* https://embracemaking.com/blogs/resources/cr10-smart-cr-6-se-easy-swap-pcb-wiring-diagrams

The 3D printable files to fit the BTT SKR Mini E3 V3 to the CR10 Smart can be found here:

* https://www.printables.com/model/422494-cr10-smart-x-skr-mini-e3-v3-mounts-and-btt-tft35-v

PrusaSlicer profile for the CR10 Smart X here:

* https://embracemaking.com/blogs/resources/cr10-smart-x-prusaslicer-configuration
* NOTE: For the filament runout detection sensor to work with files being printed from the TFT Touch screen, you MUST put M75 in the start gcode, and M77 in the end gcode!!

## **! PLEASE READ !**

These files are for the BTT SKR Mini E3 V3 mainboard with the aforementioned supported modifications in the above description. The firmware is based on Marlin bugfix 2.1.x. If you have the same setup, you can simply download the .bin file and flash your SKR Mini E3 V3 with that file.

If you have a different set of equipment (ie. extruder, runout detection sensor, auto bed levelling sensor, etc) then you must download all files and modify the configuration.h and configuration_adv.h files to suit your specific setup. There are lots of great tutorials online about configuring Marlin firmware using VScode software. My files will give you a good starting point. Eventually you will compile your custom setup to a .bin file.

Firmware update on the screen is very easy once you have your .bin file.
  
Step 1: Get 8GB SD card and format it clean. Copy the .bin file onto the SD card. You should only have 1 items on the card: the .bin file.
  
Step 2: Insert the SD card into the SKR Mini E3 V3 SD card slot and power it on. Wait 30s for the firmware update to complete.

See my videos here for the entire mainboard and screen upgrade on the CR10 Smart:


![Breakout_Render1](https://user-images.githubusercontent.com/109498075/224583184-0bb8151a-3680-42a4-bcc2-7355593700b0.JPG)

![AUX-BOARD_Render2](https://user-images.githubusercontent.com/109498075/224583201-adb482dd-7fab-422b-b6c1-a3909e319aaf.JPG)
