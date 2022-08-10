# yet-another-smart-vent

This project contains most everything needed to 3d print, assemble, and flash an MQTT Smart Vent.

## Getting Started
1. Electronics
- Components
- Assembly
2. 3d Printing
- Printing
- Assembly
3. Compile/Flash/Upload
4. Testing 

## Future features

## Philosophy

## Pull Requests

## Bugs

## Dependencies
- ArduinoJson 6.10.1
- PubSubClient 2.8.0
- WiFiManager 0.15.0
- DoubleResetDetector 1.0.3

## Development
To compile from command line:
`arduino-cli compile --fqbn esp8266:esp8266:d1 yet_another_smart_vent`

To upload from command line:
`arduino-cli upload -p /dev/ttyUSB0 --fqbn esp8266:esp8266:d1 yet_another_smart_vent`

To monitor serial output from command line:
```
sudo apt-get install minicom
minicom -D /dev/ttyUSB0 -b 9600
```
`CTRL-A` then  `x` to exit.

## References
This repo is a modifcation of [Hypfer's Midea Dehumidifier](https://github.com/Hypfer/esp8266-midea-dehumidifier).
