This project is a microcontroller-based Digital Voltmeter designed and programmed using the STM32F401RE Nucleo board. The system utilizes the internal Analog-to-Digital Converter (ADC) of the ARM Cortex-M4 processor to accurately measure external voltage levels.

The primary goal of this project is to demonstrate embedded systems programming, hardware-software integration, and peripheral configuration using STM32 HAL (Hardware Abstraction Layer) libraries.

Key Features:
Microcontroller: STM32F401RET6 (ARM Cortex-M4).

ADC Configuration: Configured to read analog signals with high precision.

PC Communication (UART): The measured voltage values are transmitted to a PC via serial communication for real-time monitoring.

Bare-metal Configuration: Pinouts and clock configurations are fully customized using STM32CubeMX.

Hardware & Software Tools:
Development Board: STMicroelectronics NUCLEO-F401RE

IDE: STM32CubeIDE

Framework: STM32 HAL Library

Simulation/Schematics: Proteus (Used for initial circuit design and voltage divider calculations)

How to Run the Project
Clone this repository to your local machine:
git clone https://github.com/ezcool2000/Digital-Voltmeter-STM32.git

Open STM32CubeIDE.

Go to File > Import > General > Existing Projects into Workspace and select the cloned folder.

If you want to check or modify the pin configurations, double-click the volt_pc.ioc file to open the graphical STM32CubeMX interface.

Build the project and flash it to your Nucleo-F401RE board.
