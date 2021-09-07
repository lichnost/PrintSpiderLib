# PrintSpider library

This repository contains source code of library for the [PrintSpider project](https://hackaday.io/project/176931-hp-printer-cartridge-control-module) of HP printer cartridge control module for Arduino/ESP32 framework.
This library is a software driver for the HP 63/302/123/803 printer cartridge control module.  You can use it to control the inkjet printing module without using the original printer directly from an Arduino, ESP32, or Raspberry PI platform. For the first time ever, inkjet technology is available for your projects in a convenient module format with the necessary easy-to-use software.

## Project stucture

Source code is organised as [PlatformIO library](https://docs.platformio.org/en/latest/librarymanager/index.html) and [Arduino IDE library](https://www.arduino.cc/en/guide/libraries) library.
Most important parts consists of:

- **./src/printspider.h** and **./src/printspider.c**: header and implementation of the library of generator of output signals sequences for control module.

Examples:

- **./examples/simple-arduino/simple-arduino.c**: source code of the simple program for jetting with color or black cartridge for Arduino platform.

## Licensing

Originally code in **./src/printspider.h** and **./src/printspider.c** borrowed from here [https://github.com/Spritetm/printercart_simple](https://github.com/Spritetm/printercart_simple) was licensed under "THE BEER-WARE LICENSE" (Revision 42). In this repository it's license is changed with Apache License, Version 2.0.

All code provided here licensed with Apache License, Version 2.0.

```
Copyright 2021 Pavel Semenov

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```