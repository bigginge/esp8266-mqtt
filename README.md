# esp8266-mqtt

## Hardware Setup
I used a generic ESP8266 NodeMCU board from [MakerHawk](https://www.makerhawk.com/products/makerhawk-3pcs-esp8266-nodemcu-lua-cp2102-esp-12f-wifi-internet-development-board-serial-wireless-module-for-arduino-ide-micropython-new-version "MakerHawk"), purchased from [Amazon](https://www.amazon.co.uk/gp/product/B07M8Q38LK/ref=ppx_yo_dt_b_asin_title_o07_s00?ie=UTF8&psc=1 "Amazon"). I should probably be concerned that the 'documentation' is a link to a single page pdf on [Google Drive](https://drive.google.com/file/d/1LNz-OE40XjNhtsZPzFIFIs9zO3uW4V6P "Google Drive").

### NodeMCU Firmware
Download and run the [NodeMCU firmware programmer](https://github.com/nodemcu/nodemcu-flasher/blob/master/Win64/Release/ESP8266Flasher.exe "NodeMCU programmer"). I changed the advanced configuration as follows:  

* Baudrate: 921600
* Flash size: 4MByte
* Flash speed: 80MHz
* SPI Mode: DIO

## Software

This is a bit of an adventure - my goal is to use a containerised build environment to test and compile the code. My first stab at this is using [PlatformIO](https://platformio.org/ "PlatformIO").




https://hub.docker.com/r/sglahn/platformio-core/dockerfile


Python 3.8-slim-buster
