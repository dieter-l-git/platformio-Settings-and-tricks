# Recomplied maple_loader.jar
This JAR file replaces the current maple_loader.jar (April 2022)
in STM32duino environment both in Arduino IDE and Platformio

The reason is, that on my Win10 development PC the maple_loader.jar crashes
on both IDE's.

I recompliled it with actual java libs and it works now on my PC.

Usage:
 - Rename the existing maple_loader.jar and lib directory
 - Copy the maple_loader.jar and the lib directory from this repo in the same directory as the existing resides.
