# Options to connect the fan

You will need a way to connect the fan to your printer. Here are some ways this could be achieved:

## MCU with enough fan ports

The easiest way would be to use a Fan-Port on your MCU, however most MCUs are already completely occupied by the Hotend-, Partcooling- and Controller-Fan. So you would need a MCU with more Fan-Ports, like the [Mellow Fly E3 Pro v3](https://www.aliexpress.com/item/1005002372751834.html) which has 4 Fan-Ports while having the same footprint as an Ender 3 Board (like BTT SKR E3).

## Additional MCU

Because Klipper supports multiple MCUs you could add another MCU however this one would need to be very small to fit the electronics compartmens of the V0. One option would be [Timmit's Klipper Expander](https://github.com/VoronDesign/Voron-Hardware/tree/master/Klipper_Expander) over on the Voron-Hardware Github.

## CAN-Bus Toolhead Board

By using a CAN-Bus Toolhead board you are freeing up 2 Fan-Ports on your main mcu, because your hotend and partcooling fan are now connected to the CAN-Board. This would allow you to connect your auxilliary fan to the mcu.

## Raspberry Pi GPIO-Pin with Transistor/MOSFET

Alternatively you can run the fan of a GPIO-Pin of your Pi by using a Transistor or MOSFET. There are quite a few guides online on how to do this, like [this one from SENSORSIOT](https://www.sensorsiot.org/variable-speed-cooling-fan-for-raspberry-pi-using-pwm-video138/). You can ignore the Python-Script, as we will control the fan through Klipper (see [Klipper Configuration](firmware_slicer.md#klipper-configuration)). The IRLZ44N MOSFET has worked fine for me for both 5V and 24V Fans.
