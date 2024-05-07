# ESPNow2MQTT
This repository contains 3 program for sending data (sensor.ino) and a ESP-NOW bridge to Serial (ESPNOW_Serial.ino) and a last part is the python program (s2m.py) that transfers the info from the sensor via the serial to a MQTT broker.

![This repository contains 3 program for sending data to a MQTT broker.](https://github.com/mats-nk/ESPNow2MQTT/blob/main/img/ESP-NOW--Serial.png)

## Arduino

`sensor.ino` - ESP-NOW Sensor program

`ESPNOW_Serial.ino` - ESP-NOW to Serial program


## Python Broker

`s2m.py` - Serial to MQTT broker program
