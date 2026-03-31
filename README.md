# [LiDAR Range Finder] — STM32

## Overview
– A real-time LiDAR distance measurement system using Nucleo-L476RG (UART @115200 baud)
– Parsed and validated serial data frames from TFMini-S sensor w/ edge case handling
– Integrated OLED display driver for live distance visualization (100 Hz refresh rate

## Hardware
- **Board:** STM32[X] Nucleo / Discovery / custom
- **Peripherals:** [e.g. UART, SPI, I2C, GPIO, ADC]
- **External components:** [e.g. sensors, displays, motors]

## Tools
- **IDE:** STM32CubeIDE
- **HAL Library:** STM32 HAL
- **Debugger:** ST-Link

## How to Run
1. Clone the repo
2. Open STM32CubeIDE → Import → Existing project
3. Build and flash to board

## Wiring
![Wiring Diagram](docs/wiring.png)

## Demo
![Demo](docs/demo.png)

## Course Info
Built as part of [Course Name] at [Your School] — [Semester]
