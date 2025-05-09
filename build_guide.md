# Build Guide

This build guide assumes that you already have soldering skills. It will only describe the locations and nuances of component installation


## 1. Break off the chips

There are 3 islands between the board halves, they are not needed during assembly. So gently press on one half of the board to break it in half, and then break off the island from the other half of the board with pliers or any other convenient way

![chips](https://github.com/inpudiy/mpa/blob/main/gallery/build/chips.png)

## 2. Diodes

There are 21 diode pads each on the back of the board. Apply flux and place the diodes cathode to square pad and anode to round pad and solder

![diode](https://github.com/inpudiy/mpa/blob/main/gallery/build/diode.png)

## 3. Hotswap socket

At the bottom of the diodes are the pads for the hotswap sockets. Apply flux and solder them on

![hotswap](https://github.com/inpudiy/mpa/blob/main/gallery/build/hotswap.png)

## 4. Reset button

On the bottom of the board on both halves, install a 3 × 4 × 2 mm Turtle Switch to reset the firmware

![reset](https://github.com/inpudiy/mpa/blob/main/gallery/build/reset.png)

## 5. On-off switch

On the TOP side of the board of both halves, install BSI-10H 

![bsi](https://github.com/inpudiy/mpa/blob/main/gallery/build/bsi.jpg)

## 6. Pin Header Female 13 pin

Break off 4 pieces of 13 pins from the long 2.54mm Pin Header Female Single Row 40 Pin and install them on the top side of the board. Carefully flip the board over with them and solder them to the back side of the board

![cribb](https://github.com/inpudiy/mpa/blob/main/gallery/build/cribb.jpg)
![cribt](https://github.com/inpudiy/mpa/blob/main/gallery/build/cribt.jpg)

## 7. Microcontroller

Using wire, diode legs or male heads, solder the board with the microcontroller into the pro micro formfactor with the controller facing upwards

![mcu](https://github.com/inpudiy/mpa/blob/main/gallery/build/mcu.jpg)

## 8. Battery

In the last soldering step, solder the wires of the batterjack to the pads and position it under the controller

> [!WARNING]
> Be careful and check with a multimeter that the BSI-10H is in the off state before soldering the battery

## 9. Case

Install the float nuts in the top of the case, install the extension for the switch, install the bottom by screwing it on and glue the non-slip rubber bands on the bottom
