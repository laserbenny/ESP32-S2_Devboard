# ESP32-S2_Devboard

This bare minimum board uses the ESP32-S2 module, it is designed to use minimal amount of current during sleep. All signals are routed to the edge of the PCB, it is also designed to fit in a breadboard.

The module is NOT 5V tolerant so make sure your UART is only 3.3V!  

1. To program the MCU first connect the UART to the RX, TX and GND pins.
2. Hold down RST and press BOOT, release the RST button and then the BOOT button.
3. The MCU shall now be in bootloader mode and can be programmed with Arduino
