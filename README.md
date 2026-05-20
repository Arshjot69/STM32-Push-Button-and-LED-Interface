STM32 Push Button and LED Interface

This project demonstrates how to interface a push button as a digital input and control an LED configured as a digital output using an STM32 microcontroller. The implementation illustrates a simple sensor-actuator system commonly used in embedded and edge-node applications.

Features
Push button interfacing using GPIO input mode
LED control using GPIO output mode
Real-time sensor-actuator interaction
STM32 HAL library implementation
STM32CubeIDE compatible project
Project Overview

The firmware continuously reads the state of a push button connected to a GPIO input pin. Based on the button state, the LED connected to a GPIO output pin is turned ON or OFF. This demonstrates the fundamental concept of embedded input sensing and output actuation.

This project is useful for understanding:

GPIO input and output configuration
Digital signal reading
Embedded control systems
Basic edge-node functionality
Sensor-actuator communication
Hardware Requirements
STM32 Development Board
Push Button
LED (Onboard or External)
Resistors (if required)
USB Cable for programming and power
Software Requirements
STM32CubeIDE
STM32CubeMX
Working Principle
System clock and GPIO peripherals are initialized.
Push button pin is configured as digital input.
LED pin is configured as digital output.
The microcontroller continuously monitors the push button state.
When the button is pressed, the LED turns ON.
When the button is released, the LED turns OFF.
Applications
Sensor-actuator systems
Industrial control systems
Smart embedded devices
Basic IoT applications
Human-machine interface projects
