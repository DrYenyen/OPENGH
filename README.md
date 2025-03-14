# OPENGH
Open source RGH

OPENGH is an open source RGH project. Nothing new here, just best effort resleases of 360 modding hardware.
Quick guide:
zip file contain:
- A folder named gerber, which is the gerbers needed to build the boards.
- A folder named source_project containing the Kicad Project for the board.
- Inside the source_project folder there is another folder named "footprint" where you will find the footprints for the project
- Some footprints came with a nazi lisense, so a link to them is provided

  Quick explanation of the boards

RGH - xc2c64a:

nano-qfg_V1: Tested and works, but the silkscreen is bad so it isn't included in the gerbers, use the project for pinout

nano-qfg_V2: Tested, except for onboard oscilator

standard-qfg: Tested and works! Only tested with  clock from 360, obboard oscilator is unknown state 

standard-qfg-ams: Tested and works! Only tested with  clock from 360, obboard oscilator is unknown state

standard-qfg-ams-reworked: Same as above, but different? Don't know why I made this, but probably works 

standard-qfg-ams-reworked-tht: THT design, 0 logic, but works! Only tested with  clock from 360, obboard oscilator is unknown state

standard-size-nano: Early alpha, but work

vanilla-hybrid_v1_1: Latest board design. Similar size to the rev. c, but totaly different design. Better and easy to find voltage reguators, less parts, better signal manipulation, MUCH better settings description, no 
unused component footprints, more granular control of settings, compatible with standard xc2c64a and QFG verion chips, vertical programming port, generally a different board design for modern timing files released by Octal450.
vanilla_v1_0: Older design of above. Also no QFG support.

RGH - xc2c128:

Nothing is tested here, probably works.


Nand_CPLD:

Nand flasher and glitch chip programmer. Tested and works 100%! Compatible with matrix nand flasher firmware found in Jrunner. Needs a bootloader to be flashed first, for which a pickit port has been added to the bottom of the board (can be used with ohter programmes too). You can also just press the pinheaders against the port, no need to solder or get expensive horizontal pinheaders. After bootloader is flashed, use firmware in Jrunner folder.

SyncRF360:
Board for connecting the 360 phat RF board to a PC, with sync using the power button so you can re-sync without connecting the RF board back to the 360.

Everything here is best effort, some things are made with older versions of KiCad, but should work with the latest as well.

Any issues let me know! Questions welcome as well!
