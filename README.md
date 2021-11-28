![IP5306 charger](https://github.com/LaskaKit/IP5306-Charger/blob/main/img/2.jpg)

# IP5306 charger - boost convertor and charger for li-ion/li-po battery. All in one. 
Are you looking for a module for for Li-Pol battery which also includes output rail for power of your device? Great, here is it - let's check what our IP5306 Charger can.
The module called IP5306 charger is able to charge you Li-ion/Li-Pol battery, also contains step-up (boost) convertor with 5V output and it able to deliver up to 2.4A to the load. 
One click enables the output, double clicks disables the output. 

The range of input power supply is 4.5 - 5.5 V and the maximum charging current may be up to 2.1A. The IP5306 includes protections of battery like undervoltage protection, overvoltage and overcurrent protection. The IP5306 has smart detection of connected device - if the output current is lower than 50 mA, it disables the output itself. 

The efficiency of IP5306 chip is really high for charging and also boost mode - in both modes the efficiency is higher than 90 %.

## Discharging
Battery | #1 LED | #2 LED | #3 LED | #4 LED
--- | --- | --- | --- |---
C >= 75% | ON | ON | ON | ON
50% <= C < 75% | ON | ON | ON | -
25% <= C < 50% | ON | ON | - | -
3% <= C < 25% | ON | - | - | -
0% <= C 3% | blinking (1.5 Hz) | - | - | -

# Charging
Kapacita | #1 LED | #2 LED | #3 LED | #4 LED
--- | --- | --- | --- |---
100% nabito | ON | ON | ON | ON
 C >= 75 % | ON | ON | ON | blinking (1.5 Hz)
50% <= C < 75% | ON | ON | blinking (1.5 Hz) | -
25% <= C < 50% | ON | blinking (1.5 Hz) | - | -
<25% | blinking (1.5 Hz) | - | - | -

The own current consumption is only 50 uA.

The module is available on https://www.laskarduino.cz/laskakit-nabijecka-li-ion-clanku-boost-ip5306-5v-2-1a/

![IP5306 charger](https://github.com/LaskaKit/IP5306-Charger/blob/main/img/1.jpg)
