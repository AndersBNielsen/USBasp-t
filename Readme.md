Status of this fork:
* Successfully flashed one ATTiny84 with another ATTiny84. (SPI) Hardware: (https://github.com/AndersBNielsen/v-usb-businesscard)
* ATTiny85 support might be broken
* TPI tested, working with ATTiny10
* Hardware folder still reflects the ATTiny85 version

SPI ISP uses PA4(SCK), PA6(MOSI), PA5(MISO), PA3 (slave reset)
TPI uses PA5(TPIDATA), PA4(SCK), PA3 (slave reset). 

### Note: This is a fork of https://github.com/cpldcpu/USBasp-t (which again is a fork of Thomas Fischl's USBasp) to support Attiny84 too. I will try to leave support for ATTiny85 intact. #

![USBasp business card](https://abnielsen.com/wp-content/uploads/2018/11/20181114_0027.jpg)

