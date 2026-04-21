# Hardware for MoistureESP project.
## Description
This project aims to use the ESP32 in low power modes, discover its capabilites for low power application. Also, this sensor project would be useful for home gardens not to forget watering.
This is not a complete product, it can be considered as a devboard.

*Software component not published yet.*
*3D case not published yet.*
## Components
- *This PCB project*
- ESP32-WROOM-32
- SOILCAP-V20 humidity measure
- DS18B20 sensor
- *SW not ready yet*
- *BMS configuration not ready yet*
## Features
- BMS cell protection.
- Overvoltage protection for battery input.
- Charger with USB (not tested).
- Wi-Fi MQTT data transmission.
- Selectable sensor measure interval.
## Interfaces
- Wi-Fi communication aimed to be used for sharing sensor data.
- Analog input for moisture sensor board (SOILCAP-V20).
- 1-Wire interface for DS18B20 temperature sensor.
- BMS I2C lines.
- UART for ESP programming and debug with RTS, DTS secondary programming feature.
- *Optional I2C for display.*
## Power
- Sized for 18650 battery cell, BMS tested with NCR18650B.
- Optinally Li-ion charger can be connected.
- Built-in USB charger was not tested.
## Prerequisites
- KiCAD v10.0.0 

## Release
- V1.0: Not tested yet, but ordered PCB.
