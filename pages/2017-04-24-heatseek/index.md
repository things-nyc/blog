---
title: HeatSeek workshop POC 
date: "2017-02-05T07:47:56.284Z"
path: "/2017-02-05-heatseek-poc/"
---

## Objective

Create a proof of concept LoraWAN node that collects data from a temperature sensor and transmits it through The Things Network to be consumed by the HeatSeek backend data system.

The final code is available at our [Github Repo](https://github.com/things-nyc/heat-seek-feather-m0-lora).

## Requirements

### Arduino Libraries

[OneWire](https://github.com/PaulStoffregen/OneWire) - Download the most recent release to ensure support for ATSAMD21G18

[TTN LMIC](https://github.com/things-nyc/arduino-lmic)

### Hardware

[DS18B20 Temperature sensor](http://www.digikey.com/product-detail/en/maxim-integrated/DS18B20/DS18B20-ND/420071) - [Datasheet](http://datasheets.maximintegrated.com/en/ds/DS18B20.pdf)

[Adafruit Feather M0 LoRa RF95](https://www.adafruit.com/product/3178)

4.7K ohm resistor

~ 3 inches of solid copper wire for LoRa antenna

### Server



## Photos!

![Sensor Pin Config](/2017-02-05-heatseek-poc/pin-config-diagram.jpg)

![Sensor Config](/2017-02-05-heatseek-poc/sensor-config.jpg)

![Sensor Plugged Into M0](/2017-02-05-heatseek-poc/connected-m0-sensor.jpg)

![TTN Payload Function](/2017-02-05-heatseek-poc/payload-function.png)