# [LiDAR Range Finder] — STM32

## Overview
- A real-time LiDAR distance measurement system using Nucleo-L476RG (UART @115200 baud)
- Parsed and validated serial data frames from TFMini-S sensor w/ edge case handling
- Integrated OLED display driver for live distance visualization (100 Hz refresh rate

## Hardware
- **Board:** STM32 Nucleo-L476RG
- **Peripherals:** UART, I2C, GPIO
- **External components:** 0.96 OLED display, TF Mini-s LiDAR 

## Tools
- **IDE:** STM32CubeIDE
- **HAL Library:** STM32 HAL
- **Debugger:** ST-Link

## How to Run
1. Clone the repo
2. Open STM32CubeIDE → Import → Existing project
3. Build and flash to board

## Future Implementation (LiDAR Scanner) 
- [ ] add step motor
- [ ] housing
- [ ] python script for real time plotting
      
## Demo
[Test 1](https://drive.google.com/file/d/1-NJwXk1A0xX-s-IomeAtq8f6QgWAQJfK/view?usp=sharing)<br>

[Test 1 Different Angle](https://drive.google.com/file/d/1a6IXdjxgUnQYEPFMO_-LWl-TF886DTvh/view?usp=sharing)


