# MKS GEN_L

# How to buy the MKS Gen_L
- [MKS GEN_L V1.0 and V2.1](https://www.aliexpress.com/item/32802151924.html)

## Features
- Gen_L CPU is ATMEGA2560-AU, 8bit 16MHZ, 5V logic level, stronger anti-interference type
- Gen_L V2.0 hardware version support TMC2208/2209 UART mode, TMC2130 SPI mode
- Support MKS TFT24/28/32/35/70...
- Support MKS LCD12864A/LCD12864/MKS MINI12864...
- Support Marlin2.0 firmware and old marlin...

- More information,you can go to [Wiki](https://github.com/makerbase-mks/MKS-GEN_L/wiki)

  
## How to Build Marlin2.0 by platformio and upload firmware
  - Open project by ATOM
  ![1-open_project](https://github.com/makerbase-mks/MKS-GEN_L/blob/master/Picture/1-open_project.png "1-open_project")
  - Open platformio.ini file, set default_envs = megaatmega2560
  ![2-megaatmega2560](https://github.com/makerbase-mks/MKS-GEN_L/blob/master/Picture/2-megaatmega2560.png "2-megaatmega2560")
  - Open configuration.h file, set board as MKS_GEN_L or MKS_GEN_L_V2
  ![3-setboard](https://github.com/makerbase-mks/MKS-GEN_L/blob/master/Picture/3-setboard.png "3-setboard")
  - Connect board by USB and set serial
  ![4-connectboard](https://github.com/makerbase-mks/MKS-GEN_L/blob/master/Picture/4-connectboard.png "4-connectboard")
  - Build and upload firmware
  ![5-build_upload](https://github.com/makerbase-mks/MKS-GEN_L/blob/master/Picture/5-build_upload.png "5-build_upload")
