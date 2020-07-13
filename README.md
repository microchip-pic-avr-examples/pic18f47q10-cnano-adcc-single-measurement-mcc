<div id="readme" class="Box-body readme blob js-code-block-container">
<article class="markdown-body entry-content p-3 p-md-6" itemprop="text"><p><a href="https://www.microchip.com" rel="nofollow"><img src="images/MicrochipLogo.png" alt="MCHP" style="max-width:100%;"></a></p>

# PIC18F47Q10 ADCC Single Conversion Configuration Example

The PIC18F47Q10 features one 10-bit ADCC module.
In this demo, the ADCC peripheral is used to read a value from an analog pin connected to a potentiometer. 

## Related Documentation 

- [Getting started with the ADCC tech brief](https://www.microchip.com/DS90003263)
- [PIC18F-Q10 Family Product Page](https://www.microchip.com/design-centers/8-bit/pic-mcus/device-selection/pic18f-q10-product-family)

## Software Used
- MPLAB® X IDE 5.30 or newer [(microchip.com/mplab/mplab-x-ide)](http://www.microchip.com/mplab/mplab-x-ide)
- MPLAB® XC8 2.10 or a newer compiler [(microchip.com/mplab/compilers)](http://www.microchip.com/mplab/compilers)
- MPLAB® Code Configurator (MCC) 3.95.0 or newer [(microchip.com/mplab/mplab-code-configurator)](https://www.microchip.com/mplab/mplab-code-configurator)
- MPLAB® Code Configurator (MCC) Device Libraries PIC10 / PIC12 / PIC16 / PIC18 MCUs [(microchip.com/mplab/mplab-code-configurator)](https://www.microchip.com/mplab/mplab-code-configurator)
- Microchip PIC18F-Q Series Device Support (1.4.109) or newer [(packs.download.microchip.com/)](https://packs.download.microchip.com/)

## Hardware Used
- PIC18F47Q10 Curiosity Nano [(DM182029)](https://www.microchip.com/Developmenttools/ProductDetails/DM182029)
- Curiosity Nano Base for Click boards™ [(AC164162)](https://www.microchip.com/Developmenttools/ProductDetails/AC164162)
- POT Click board™ [(MIKROE-3402)](https://www.mikroe.com/pot-click)

## Setup
The PIC18F47Q10 Curiosity Nano Development Board is used as test platform, along with the Curiosity Nano Base for Click boards™ and the POT Click board™.

The following configurations must be made for this project:

| Pin           | Configuration      |
| :----------: | :----------------: |
| RA0           | Analog Input       |

<img src="images/HWsetup.png" alt="Hardware Setup" width="480"/>

## Operation:
1. Connect the board to the PC.

2. Open the *pic18f47q10-cnano-adcc-single-measurement-mcc.X* project in MPLAB® X IDE.

3. Set *pic18f47q10-cnano-adcc-single-measurement-mcc* project as main project. Right click on the project in the *Projects* tab and click *Set as Main Project*:
<br><img src="images/main.PNG" width="600">

4. Select the *PIC18F47Q10 Curiosity Nano* in the *Hardware Tool* section of the project settings:
  - Right click on the project and click *Properties*;
  - Select the *PIC18F47Q10 Curiosity Nano* (click on the SN) in the *Hardware Tool* tab and then click *OK*:
<br><img src="images/prop.PNG" width="600">


5. Run the code in debug mode: right click on the project and click *Debug*:
<br><img src="images/debug.PNG" width="600">


6. Pause the debug process by clicking the *Pause* button (or click *Debug -> Pause* in the Menu bar):
<br><img src="images/pause.PNG" width="600">


7. Add *adcVal* variable to the *Variables window*: right click on the `adcVal` variable in main.c file and click *New Watch*:
<br><img src="images/watch.PNG" width="600">


The ADC value on RA0 pin will be read only once, before the program gets to the infinite loop. The value of `adcVal` will reflect the potentiometer position.
<br><img src="images/var.PNG" width="600">

## Summary
This project showcases how the Analog-to-Digital Converter with Computation (ADCC) on the new PIC18-Q10 can be used to read an analog value from a pin.