# UCSD-IARC-SummerTesting
This repository contains code for UCSD's International Aerial Robotics Competition. The code here is for a Nucleo F446RE, which is used to develop firmware that will be used on our final Quadcopters in the future

## Directory Structure
Directory | Description
----------|-----
Drivers   | HAL and CMSIS Drivers generated by STM32CubeMX
Middlewares | FreeRTOS Source Code
Src/Inc | Autogenerated source/header files from STM32CubeMX + user-created testing code for IARC Firmware
IARC  | Portable firmware files developed by us that use HAL Libraries. Main deliverable of this repository

## Current Firmware Files
### MPU\_COMMON
Driver for Invensense 9-axis accelerometers. Supports mpu9255 and mpu9150 devices

### SSD1306 and Fonts
Driver for the 128x32 I2C OLED Display found on Adafruit

## Main Developers
* Georges Troulis
* *more people*
