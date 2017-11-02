# ttn-basel-feinstaub
Creat your own particulate matter sensor with an ESP32 and LoRaWAN (TheThingsNetwork)

## Requirements
* Arduino IDE with ESP32 support (https://github.com/espressif/arduino-esp32)
* ...

## Folder description
* Feinstaub_LoRa_SDS011_DHT22 contains the ESP32 version with LoRaWAN support (TheThingsNetwork)
* sensor-software contains the original ESP8266 version from luftdaten.info
* NodeRed-flow contains the event driven data handler for Node-Red in order to get data from the ttn backend and pushing it into the luftdaten.info database
