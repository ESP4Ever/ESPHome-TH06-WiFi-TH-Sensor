![](/pictures/Tuya Wi-Fi TH06 Sensor.png)
# Tuya to ESPHome conversion of the TH06 WiFi Temperature & Humidity Sensor with LCD display
This sensor is built on WB3S Tuya chip which shall be replaced to a ESP8266-based module.
For such mods I'm using ESP07S because it has all pull-up/down resistors inside so no external components required, besides that it has 4MB flash - a lot of space for your code and OTA image. The only disadvantage of this module is an external antenna which require a "Tetris-playing", fitting it into small devices.

WARNING:
If you plan to use a heatgun for the module removal you have to remove the LCD display first or it most probably will be permanently damaged.
I used a soldering iron with a wide tip and a needle.

What's inside:
![What's inside-1](/pictures/inside1.jpg)
![What's inside-2](/pictures/inside2.jpg)
![What's inside-3](/pictures/inside3.jpg)

After mod:
![After mod-1](/pictures/after1.jpg)
![After mod-2](/pictures/after2.jpg)
