# Cumin Lander

This is a firmware repository for the Cumin Lander based on the Seeedstudio XIAO nRF52840. You can find the documentation for this project on my website [here.]( https://www.bhoite.com/sculptures/cumin-lander/)

![Cumin Lander](https://github.com/mohitbhoite/cumin-lander/blob/main/cumin-lander-expanded.png)

## Required libraries:

You'll need to install [Arduino BSP for Adafruit Bluefruit nRF52 series](https://github.com/adafruit/Adafruit_nRF52_Arduino/tree/master) first. Then make sure you have the following libraries.

- BLE: [Adafruit Bluefruit](https://github.com/adafruit/Adafruit_BluefruitLE_nRF51)
- Sensor: [Adafruit BME280](https://github.com/adafruit/Adafruit_BME280_Library)
- Display: [Adafruit SSD1306](https://github.com/adafruit/Adafruit_SSD1306)
- Graphics: [Adafruit GFX](https://github.com/adafruit/Adafruit-GFX-Library)
- Memory: [Adafruit Flashtransport](https://github.com/adafruit/Adafruit_SPIFlash/tree/master)

I used the Arduino IDE v1.8.13 to compile and flash the code on to the nRF52840. Other versions may or may not work.

## FORKED MODS

I can confirm working on Arduino IDE 2.3.4,
libraries versions:  
Adafruit BME280 - 2.2.4  
Adafruit BusIO - 1.16.3  
Adafruit GFX - 1.11.11  
Adafruit SSD1306 - 2.5.13  
Adafruit Unified Sensor - 1.1.15  
Time - 1.6.1  

I have added UART menu to handle Enable/Disable Leds, screen, play melody on demand, handle alarm and check its status.

plan to add deep sleep for choosen time
