# LoRa Gateway FeatherWing

## Description
This is a LoRa Gateway board designed for FeatherWing ecosystem, based on Semtech SX1303 Digital Baseband Chip and Ublox EVA-7M GPS module. Board schematic is largely based on the SX1303 reference design, and this board is designed for 915Mhz operation.
![](https://i.imgur.com/zjJWZrJ.jpg)

**This Design is still in development process, please use with caution**  
Currenly I tested receiver function with Rapsberry Pi, but I have some issue with it transmit package to my RPI GW, though using SDR I can see the package sending out, not sure if it is a SW or HW issue. 

**And currently the MCU software is in development process**  
~~Help~~

## FeatherWing Connection usage
SX1303 uses the SPI bus an two GPIO (CS and Reset on D5 and D6) on the FeatherWing to communicate with host MCU, and GPS module uses the UART pins and a GPIO for pulse-per-second output on A5.

## Design Tool
KiCad v5.99 is used to design the board, and JLCPCB to manufactured the board.
![](https://i.imgur.com/oUBsXb7.png)
![](https://i.imgur.com/TOjzmLP.png)
I'm pretty noob about the KiCad stuff, so any feedback is welcome.

## Parts sourcing
I sourced most parts from Mouser, here is the parts list:
https://www.mouser.com/ProjectManager/ProjectDetail.aspx?AccessID=11549c8008

Note: SMA connector is not included, because it is related to the board thickness your are using, I'm using 1mm 4 layer pcb, and I can't find the connector on Mouser.


CC BY-SA 4.0
