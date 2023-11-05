# STM32 Microcontroller 
 
The designed PCB features an STM32F4RTG6 microcontroller which is part of the STM32F4 series known for its high performance and with floating point unit (FPU) that supports ARM Cortex-M4 core. The board integrates an MPU6050, which is a popular 6-axis MotionTracking device combining a 3-axis gyroscope and a 3-axis accelerometer.

## Microcontroller Core:

STM32F4RTG6: ARM Cortex-M4 core with FPU, running at high frequencies, capable of driving complex applications that require floating-point calculations and advanced control algorithms.
Sensors:

MPU6050: Offers onboard Digital Motion Processing™ (DMP™) capable of processing complex 6-axis MotionFusion algorithms. The sensors communicate via I2C protocol, which is set up on the STM32F4 microcontroller.
Power Supply:

The board appears to have a +5V input power supply, with onboard voltage regulation to provide +3.3V needed by both the STM32 microcontroller and the MPU6050 sensor.
Voltage regulators (like AMS1117-3.3) are used to step down the voltage.
Various capacitors are placed near power inputs and voltage regulators to stabilize the power supply and reduce noise.
Connectivity:

The microcontroller’s I/O pins are brought out to headers, providing the ability to connect to other peripherals and sensors.
The schematic shows decoupling capacitors and pull-up resistors on I2C lines which are critical for signal integrity.
Programming and Debugging Interface:

There appears to be a programming interface, possibly using Serial Wire Debug (SWD), which is standard for STM32 devices. This allows for programming and debugging of the microcontroller directly on the board.
Oscillator:

A crystal oscillator is used for providing an accurate clock signal to the STM32F4 microcontroller.
Load capacitors are connected to the crystal to ensure proper oscillation.
General PCB Design Notes:

The schematic is organized into functional blocks, which simplifies the complexity and helps in understanding the circuit.
Each IC has decoupling capacitors close to the power supply pins to reduce power supply noise and for maintaining signal integrity.
The use of pull-up resistors on the reset line and buttons indicates attention to proper microcontroller reset and user input handling.

## Schematic:
![Schematic.jpg](https://raw.githubusercontent.com/prdpgit/STM32-Microcontroller-/main/Schematic.jpg)

## PCB layout
![PCB layout](https://raw.githubusercontent.com/prdpgit/STM32-Microcontroller-/main/PCB_page-0001.jpg)

## 3D PCB render
![PCB 3D1](https://raw.githubusercontent.com/prdpgit/STM32-Microcontroller-/main/STM32.jpg)
![PCB 3D2](https://raw.githubusercontent.com/prdpgit/STM32-Microcontroller-/main/STM321.jpg)
