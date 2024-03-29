# PlatformIO-OSEC
Migrated Stancecokes "Open Source E-Bike Controller" to what I see as an easier and more composed platform.

Usage:
1. Clone repository
2. Open project with PlatformIO in Visual Studio Code
3. Use included "Java Configuration Tool" to generate a config.h file
4. Build
5. Wire up ST-Link and Upload!


Notes:
1. PlatformIO automatically downloads the required tools and libraries and uses these in a separate environment,
this includes STM8 Binutils, Standard Peripheral Library and SDCC 4.1.0.
2. Use the included "Java Configuration Tool" to generate a config.h and either copy the contents or move the generated file to the "src" folder to apply a new config.
3. Even though the repository contains the same code as the original **master branch**, I've taken upon myself to remove everything that is not directly associated with the firmware code. Said files can be retrieved from Stancecokes repository.

For issues with the firmware or wiki access, visit the original repository  
https://github.com/stancecoke/BMSBattery_S_controllers_firmware
