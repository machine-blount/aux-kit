# aux-kit
***Your new auxiliary framework***

Aux-kit is designed to be an all in one auxiliary/supplementary solution for any electric-powered solar car teams competing in the National Solar Car Challenge. In its current version It is designed as a Pi-HAT which connects to multiple expansion boards for quick iteration on separate parts of the system. 

All of the boards are only double sided so if you have an iso-mill or a fiber laser you can cook yourself up an aux-kit quickly for cheap. Most of the components are common but you may have to look out for:

- CAT24C256(EEPROM)
- DMMT5401-7(PNP Transistor Pair), 
- DMG2305UX(P-Channel Enhancement Mode MOSFET), 
- LM2596(Step-Down Converter).

## v1.0.0 Feature List
- Horn Control 
- Left Turn Signals  
- Right Turn Signals
- Hazards
- Brake Lights
- Battery Monitor 
- On-Board 12V-5V Step-Down Converter

Currently aux-kit only supports the basic supplementary/auxiliary requirements for the ESPV division but this is why the board leaves you with ~35mm x 22mm of square free real estate for any additional hardware. Additionally aux-kit has solder jumpers on the underside of the board which allow you to choose whether to control certain features programmatically through the Pi directly, or if you just want the integrated analog control to handle it for you. 

Initially I had designed aux-kit for my own team but because of the collaborative environment inside of the NSCC I had second thoughts and decided to open source the project for any another team to contribute. 
