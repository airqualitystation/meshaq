#  Air Quality Station on LoRa mesh networks (Meshcore, Meshtastic)

## Hardware

* Wio S3 (ESP32S3 + SX1262)
* Sensors
    * Plantower PMS7003 → particule matter PM1 / PM2.5 / PM10
    * Sensirion SEN54/SEN55 → particule matter, temperature, humidity, VOC, NOx
    * Grove Multichannel Gas Sensor v2 → CO, NO₂, VOC, etc.
    * VEML7700 → luminosity
    * SHT31/SHT41 → temperature/humidity
    * TMP117 → high precision temperature
    * MAX30205 → high precision temperature
    * DS18B20 → temperature (OneWire)
    * MAX31865 + PT100/PT1000 → low and high temperature 

## Firmwares

* Meshtastic (telemetry)
* Meshcore (simple_sensor + MQTT observer when Wifi AP connection)
