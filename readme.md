<div id="readme" class="Box-body readme blob js-code-block-container">
<article class="markdown-body entry-content p-3 p-md-6" itemprop="text"><p><a href="https://www.microchip.com" rel="nofollow"><img src="images/MicrochipLogo.png" alt="MCHP" style="max-width:100%;"></a></p>

# PIC18F47Q10 ADCC Single Conversion Configuration Example

## Objective:
The PIC18F47Q10 features one 10-bit ADCC module.
In this demo, the ADCC peripheral is used to read a value from an analog pin connected to a potentiometer. 

<img src="images/HWsetup.png" alt="Hardware Setup" width="480"/>

## Resources:
- Technical Brief Link [(linkTBD)](http://www.microchip.com/)
- MPLAB® X IDE 5.30 or newer [(microchip.com/mplab/mplab-x-ide)](http://www.microchip.com/mplab/mplab-x-ide)
- MPLAB® XC8 2.10 or newer compiler [(microchip.com/mplab/compilers)](http://www.microchip.com/mplab/compilers)
- MPLAB® Code Configurator (MCC) 3.95.0 or newer [(microchip.com/mplab/mplab-code-configurator)](https://www.microchip.com/mplab/mplab-code-configurator)
- PIC18F47Q10 Curiosity Nano [(DM182029)](https://www.microchip.com/Developmenttools/ProductDetails/DM182029)
- Curiosity Nano Base for Click Boards™ [(AC164162)](https://www.microchip.com/Developmenttools/ProductDetails/AC164162)
- POT click board™ [(MIKROE-3402)](https://www.mikroe.com/pot-click)
- [PIC18F47Q10 datasheet](http://ww1.microchip.com/downloads/en/DeviceDoc/40002043D.pdf) for more information or specifications.

## Hardware Configuration:
The PIC18F47Q10 Curiosity Nano Development Board  [(DM182029)](https://www.microchip.com/Developmenttools/ProductDetails/DM182029) is used as the test platform, along with the Curiosity Nano Base for Click Boards™ [(AC164162)](https://www.microchip.com/Developmenttools/ProductDetails/AC164162) and the POT click board™ [(MIKROE-3402)](https://www.mikroe.com/pot-click).
The following configurations must be made for this project:
- RA0 pin - Configured as analog input 

## Demo:
Run the code with a debugger, stop it and check the value of the variable to see the result. 

