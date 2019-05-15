## Introduction

zesta2 is improvement of the first zesta project. This will be a complete
make-from-scratch laptop power supply module. The zesta project which I currently use works
well but due to the parts not made by me, there is so much constraints that I am facing.

The result is just to make my own power supply/laptop charger from scratch. I will be in
control of the specs and most important, the design. Also I will add some culture to the
charger to make it more Kenyan. The charger shall still be housed in a zesta jam can.

## Main Objective

Learn and understand how Switched Mode Power Supplies (SMPS) work.

## What is a Switched Mode Power Supply?

Preety much all latops come with an extra device called a charger. Its main function is to
supply power to charge the laptop's battery.

To do this it converts the mains 240V AC to 19V DC which the laptop requires. This conversion
is a combination of the following steps:

* Input - 240V(AC)
* Rectification and Filtering - High Voltage DC
* Transformation - AC
* Rectification and Filtering - 19V DC

## Specs

* Input: AC 240V
* Output: DC 19.5V
* Power: 120W
* Frequency: 60Hz

## Proposed Features

* I2C Interface
* USB 3.0 Interface
* Opensource
* Raspberry Pi Controller
* Microcontroller controlled power supply
* Dashboard for online/offline monitoring

## Safety First

* High voltage AC it is lethal.
* All stages in SMPS circuit have High voltage AC/DC, Handle with extreme care.
* Do not attemp to remake this project if you are not qualified to do so.

## Circuit Diagram

![circuit-diagram]( http://www.theorycircuit.com/wp-content/uploads/2017/08/smps-circuit-diagram-12v-1a-tny267.png)

## References

* [LearnAboutElectronics](http://www.learnabout-electronics.org/PSU/psu30.php)
* [ElectronicsTutorials](https://www.electronics-tutorials.ws/power/switch-mode-power-supply.html)
* [HardwareSecrets](https://www.hardwaresecrets.com/anatomy-of-switching-power-supplies/)
* [ElectronicsDesigns](https://www.hardwaresecrets.com/anatomy-of-switching-power-supplies/)
* [Theory Circuit ](http://www.theorycircuit.com/simple-smps-circuit/)
