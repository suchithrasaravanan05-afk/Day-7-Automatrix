# Day 7: DHT11 Readout

This project connects a DHT11 temperature and humidity sensor to an ESP32 and prints readings to the Serial Monitor every 2 seconds.

## Components

- ESP32 DevKit v1
- DHT11 sensor

## Connections

- DHT11 VCC → ESP32 3V3
- DHT11 GND → ESP32 GND
- DHT11 DATA → ESP32 GPIO 15

## Wokwi Simulation

[Run the simulation](https://wokwi.com/projects/476469838686994433)

## How to use

1. Start the Wokwi simulation.
2. Open the Serial Monitor.
3. View the temperature and humidity readings, which update every 2 seconds.

## Arduino Library

Install the **DHT sensor library by Adafruit**. If prompted, also install **Adafruit Unified Sensor**.
