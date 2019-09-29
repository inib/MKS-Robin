# config for TwoTrees Sapphire Pro

**this is an older version of marlin bugfix 2.0 - some stuff is old/bugged**
I can't get the TouchPanel working on the current bugfix branch

**with new bootloader that comes with FW 1.0.3 you have to rename the file to *Robin_nano35.bin* instead of *Robin_nano.bin***

* changed to Sapphire geometry and my boundries
* activated several options, including LCD bed leveling, parking, filament change
* added my PID values for the 50 W heater (@ 200° C) and bed (@ 50° C)
* babystepping
* disables some libs that caused issues

# Mks-Robin Nano
Mks-Robin Nano Firmware version description

Mks-Robin Nano V1.0.0

     Initial version
     
1.Firmware options

Mks-Robin Nano: Robin_nano.bin

2.Mks-Robin Nano V1.0.0 function description

  2.1.Control chip: 32-bit ARM
  2.2.External WIFI module for cloud printing
  2.3.Multi-language:Chinese;English;Russian;Spanish;French;Italian
  2.4.Continue printing after power off
  2.5.Dislay:TFT
  
Mks-Robin Nano V1.0.1
  1.Fixed a bug that the target temperature became zero after change filament return during printing.
  2.Fixed bug that steper driver of 8825 could not be used normally.
  3.Added configuration item for Inverting Stepper Enable Pins of XYZE axis.
