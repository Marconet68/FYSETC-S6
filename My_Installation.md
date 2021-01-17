#My PC config
Ubuntu ver 20.04



# Firmware Update
## SD card
Not working for me with RepRapDiscount full graphic Smart controller
The doc says:
 If you choose to upload the firmware with a sdcard. First you need to connect a sdcard module to the S6 EXP2 port. Basically , you can use any kind of LCD screen that contain sdcard module. But if you can't make it work , check if your sdcard module's SPI CS pin connected to PA4 pin in S6 board .
https://wiki.fysetc.com/FYSETC_S6/ 

Note: RepRapDiscount full graphic Smart controller
The connection is a bit tricky, youhave to invert connector
see: https://forum.fysetc.com/d/328-fysetc-s6-rep-rap-discount-lcd-only-backlight


## Bootloader (
install stm32cubeprogrammer (version 2.6 which comes with java)

To enter FDU mode i need to connect boot to 3.3V not to ground
Take care to downloas at the right start adress 
Otherwise you need to reload the bootloader.


