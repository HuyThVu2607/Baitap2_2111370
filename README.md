# Embedded Programming Assignment 2

## Introduction
This project is the second assignment for the Embedded Programming course at EE3031. 
The aim of the project is to develop an embedded application using the STM32F103C8T6 microcontroller to control an LED through a button press and UART communication.

## Hardware Requirements
- **Microcontroller**: STM32F103C8T6 (STM32 Blue Pill board can be used)
- **Power Supply**: USB or external 3.3V source
- **Additional Components**:
  - LED and appropriate resistor
  - Push button
  - USB cable for programming and UART communication

## Installation
### Software
To program the STM32F103C8T6, you will need the following software:
- [STM32CubeIDE](https://www.st.com/en/development-tools/stm32cubeide.html) - IDE from STMicroelectronics for programming STM32 microcontrollers.
- [STM32CubeMX](https://www.st.com/en/development-tools/stm32cubemx.html) - For configuring the microcontroller and generating initialization code.
- [FreeRTOS](https://www.freertos.org/) - The real-time operating system that will be used in the project.

### Hardware Setup
1. **Setting up the LED and button on the STM32 board**:
   - Connect the LED's anode through a resistor to a GPIO (e.g., PC13).
   - Connect the LED's cathode to GND.
   - Connect one pin of the button to another GPIO (e.g., PA0).
   - Connect the other pin of the button to GND.

2. **Configuring UART**:
   - Connect STM32's TX, RX to a USB-to-UART converter module for communication with the computer.

## Usage
Running the program will allow the user to:
- Control the state of the LED via UART with commands `ON`, `OFF`, and `TOGGLE`.
- Toggle the LED state using the button on the board.

## Notes
- Ensure proper licensing for all used software.
- Refer to supporting documentation from ST and FreeRTOS for more detailed configurations.

## Contact
- Implemented by: [HuyThaiVu_2111370]
- Email: [huy.vuvth2607@gmail.com]
- GitHub: [https://github.com/HuyThVu2607]
