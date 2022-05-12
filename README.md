# Arduino custom board package for Atmega2560

Provides a modified stk500v2 bootloader to support alternate slower (software UART) baudrate programming for pyduino hydrogeologger from the default 1155200 baud for the Atmega2560 chipset.

## Supported Chipset

* Atmega2560 (Arduino Mega)

## Available Baudrate

* 2400 (Hydrogeologger Default)
* 4800
* 115200 (Arduino Default)

## Requirements/Dependencies
Requires an ISP programmer to program bootloader. Some examples...
* AVRISP mk2
* USBTiny ISP
* USBasp

To use a secondary Arduino board as ISP programmer, follow the link 
https://docs.arduino.cc/built-in-examples/arduino-isp/ArduinoISP#use-arduino-as-isp


# How to install

## Add or remove hydrogeolog (third-party) boards in Arduino IDE Boards manager

Add the following line to *Additional Boards Manager URLs* text field in Arduino IDE preferences.
```
https://raw.githubusercontent.com/hydrogeologger/hydrogeolog-board/main/package_hydrogeolog_index.json
```

To learn how to add a third-party board package to Arduino IDE, follow the link.

https://support.arduino.cc/hc/en-us/articles/360016466340-Add-or-remove-third-party-boards-in-Boards-Manager

## Add hydrogeolog board to Arduino IDE
Search for hydrogeolog board from Arduino IDE boards manager.

Follow the link to Learn how to add a board to Arduino IDE.

https://support.arduino.cc/hc/en-us/articles/360016119519-Add-a-board-to-Arduino-IDE
