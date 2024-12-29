# IoT Projects with STM32

This repository contains IoT projects developed using the STM32 microcontroller, showcasing a variety of sensors, modules, and functionalities. The aim of these projects is to demonstrate the capabilities of STM32 in real-world IoT applications, integrating hardware and software solutions efficiently.

## Table of Contents
- [Introduction](#introduction)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Features](#features)
- [Project Directory Structure](#project-directory-structure)
- [Getting Started](#getting-started)
- [Project Descriptions](#project-descriptions)
- [License](#license)

## Introduction
STM32 microcontrollers are widely used in IoT applications due to their versatility and power efficiency. This repository provides multiple projects utilizing components like sensors (ultrasonic, LDR, DHT), actuators (relay), and modules (LCD, I2C) to explore the features of STM32.

## Hardware Requirements
The following components are used across the projects:

1. **STM32 Microcontroller**
2. **Ultrasonic Sensor** (e.g., HC-SR04)
3. **Light Dependent Resistor (LDR)**
4. **Push Button**
5. **Relay Module**
6. **LCD Module**
7. **DHT Sensor** (e.g., DHT11/DHT22 for temperature and humidity)
8. **Resistors**
9. **Breadboard**
10. **LEDs**
11. **STM32CubeMX** (for hardware configuration)
12. **Arm Keil IDE**
13. **PuTTY** (for serial communication)

## Software Requirements
- **STM32CubeMX**
- **Keil uVision IDE**
- **PuTTY** (or any terminal emulator)
- **ST-LINK Utility**
- **Embedded C** programming knowledge

## Features
The repository covers the following functionalities:

1. **Ultrasonic Sensor Integration**: Measuring distance using PWM and timer frequency.
2. **LDR with ADC**: Reading light intensity and converting it to digital values.
3. **Interrupt Handling**: Using push buttons for triggering specific actions.
4. **Relay Control**: Managing high-power devices via STM32.
5. **LCD Interface**: Displaying data using I2C communication.
6. **DHT Sensor**: Reading temperature and humidity data.
7. **PWM Frequency Control**: Adjusting LED brightness.
8. **Timer Frequency**: Configuring timers for precise control.

## Project Directory Structure
```plaintext
IoT-Projects-with-STM32/
|-- README.md
|-- LICENSE
|-- docs/
|   |-- setup-guide.md
|   |-- troubleshooting.md
|-- projects/
|   |-- ultrasonic_sensor/
|   |   |-- source/
|   |   |-- include/
|   |   |-- README.md
|   |-- ldr_with_adc/
|   |-- interrupt_handling/
|   |-- relay_control/
|   |-- lcd_interface/
|   |-- dht_sensor/
|   |-- pwm_frequency/
|   |-- timer_frequency/
```

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/arnobchak/IoT-Projects-with-STM32.git
   ```

2. Set up your STM32 development environment using STM32CubeMX and Keil.

3. Connect the required components as per the project schematic (provided in the respective project folder).

4. Load the code into the STM32 microcontroller using the ST-LINK Utility.

5. Use PuTTY or a similar terminal to view serial output.

## Project Descriptions

### Ultrasonic Sensor Integration
- **Description**: Measures distance using the HC-SR04 ultrasonic sensor.
- **Concepts**: PWM, Timer Frequency.
- **Usage**: Proximity sensing in robotics.

### LDR with ADC
- **Description**: Reads light intensity and converts it to digital values.
- **Concepts**: Analog-to-Digital Conversion (ADC).
- **Usage**: Ambient light detection for smart lighting.

### Interrupt Handling
- **Description**: Demonstrates interrupt handling using a push button.
- **Concepts**: External Interrupts.
- **Usage**: Event-driven programming.

### Relay Control
- **Description**: Controls a relay to manage high-power devices.
- **Concepts**: Digital Output.
- **Usage**: Home automation.

### LCD Interface
- **Description**: Displays data using an LCD module.
- **Concepts**: I2C Communication.
- **Usage**: Real-time monitoring systems.

### DHT Sensor
- **Description**: Reads temperature and humidity data.
- **Concepts**: Digital Communication.
- **Usage**: Environmental monitoring.

### PWM Frequency Control
- **Description**: Adjusts LED brightness using PWM.
- **Concepts**: Pulse Width Modulation (PWM).
- **Usage**: Dimmable lighting.

### Timer Frequency
- **Description**: Configures timers for precise control.
- **Concepts**: Timer Configuration.
- **Usage**: Time-sensitive applications.

## License
This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
Feel free to contribute to this repository by creating pull requests or reporting issues!

