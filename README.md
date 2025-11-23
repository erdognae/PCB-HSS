# Ergenekon: Pico  Based Multi-Purpose Control Board

## Overview
Ergenekon is a custom carrier board designed for the **Raspberry Pi Pico W**, developed by the **Gazi Cyber Research and Development (Gazi Siber Araştırma ve Geliştirme)** team. This hardware serves as a compact, all-in-one solution for 2-axis robotic applications, IoT devices, and laboratory automation projects requiring independent power regulation and wireless connectivity.

## Key Features

### 1. Microcontroller
* **Core:** Designed for **Raspberry Pi Pico W** (RP2040).
* **Connectivity:** Supports WiFi and Bluetooth LE via the Pico W module.
* **IO Access:** Breakout pins for unused GPIOs are available on the board.

### 2. Power Management System
The board features a robust power stage with **3 independent Buck Converters (LM2596)**:
* **5V Fixed Rail:** Powers the MCU, logic circuits, and OLED display.
* **2x Adjustable Voltage Rails:** dedicated power lines with potentiometer adjustments for motors, fans, or external peripherals (e.g., 12V).
* **Input:** Wide range DC input via Barrel Jack.

### 3. Motion Control
* **Dual Stepper Drivers:** 2x sockets for A4988/DRV8825 compatible stepper motor drivers.
* **Axis Control:** Dedicated headers for X and Y axis (STEP/DIR/ENABLE).
* **Microstepping:** On-board DIP switches for hardware microstepping configuration.

### 4. Peripherals & Output
* **Display:** I2C header designed for **0.96" SSD1306 OLED** screens.
* **High Power Outputs:** 2x MOSFET-controlled outputs (PWM capable) for driving fans, heaters, or solenoids.
* **Cooling:** Dedicated fan ports with adjustable voltage support.

## Technical Specifications
* **Input Voltage:** 12V - 24V DC
* **Logic Voltage:** 3.3V / 5V
* **Motor Interface:** 4-pin JST/Header connectors (StepX, StepY)
* **Dimensions:** Custom form factor with mounting holes.

## Applications
* 2-Axis CNC Plotters or Laser Engravers.
* Wireless Pan/Tilt Camera Gimbals.
* IoT-based Environment Monitoring Stations.
* Educational Robotics Kits.


#### This project is developed for educational purposes at **Gazi University**.
####The card is a basic design and can be improved much more and may have shortcomings.

<img width="787" height="570" alt="3d" src="https://github.com/user-attachments/assets/91052115-2c1e-477f-bb1c-89e7ddb54da8" />


