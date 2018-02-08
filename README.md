# SPEEDUINO-PSOC5
 
This is a special version of the great speeduino ecu code made to run on the Cypress PSOC5 

This version don't have the same features so please look at the real speeduino before you continue

https://speeduino.com/wiki/index.php/Speeduino
https://github.com/noisymime/speeduino

I have made a special ARDUINO speeduino version for the Cypress CY8CKIT-059 based on the loosly on the great work from sparkfun
On top of this I have made a "plugin" to PlatformIO enabling you to use ATOM/PlatformIO

Bootloader:

Source code - if you want to change it PSOC Creator 4.0 is the one to use. There is a update.bat file that you can use after you have 
corrected the paths in it.

Root folder for the PSOC5 code for Bootloader and ARDUINO-speeduino
https://github.com/J-f-Jensen/SPEEDUINO-PSOC5

Cypress CY8CKIT-059 board:
http://www.cypress.com/documentation/development-kitsboards/cy8ckit-059-psoc-5lp-prototyping-kit-onboard-programmer-and?source=search&keywords=cy8ckit-059

After the bootloader is loaded and tested you can remove the programming board. Just use the upload function in ATOM/PlatformIO when
you want to upload new code

To install the PSOC5 support in ATOM/PlatformIO just copy the folders from DOTplatformio to the .platformio folder in the root folder
of your user, example: c:\users\bruger\.platformio


