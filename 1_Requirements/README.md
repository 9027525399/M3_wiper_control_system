# Requirements
# introduction
A windscreen wiper or windshield wiper or wiper blade is a device used to remove rain, snow, ice, washer fluid, water from a vehicle's front window.Current car wipers works on the principle of manual switching. The traditional wiper system requires driver's constant attention in adjusting the wiper speed. Traditional windshield wiper speed constantly varies according to time and vehicle’s speed which not only require driver’s attention but also causes a certain level of discomfort to the driver's vision and serves as a source of distraction which increases the risk of accidents.So,to offer comfort to the driver and essentially reduce the risk of accidents, an automatic rain sensing device has become a necessity, as they work to minimize the time of the driver
# Requirements for the project
## STM32CubeIDE
STM32CubeIDE is an advanced C/C++ development platform with peripheral configuration, code generation, code compilation, and debug features for STM32 microcontrollers and microprocessors. It is based on the Eclipse/CDT framework and GCC toolchain for the development, and GDB for the debugging. It allows the integration of the hundreds of existing plugins that complete the features of the Eclipse IDE.
## Xpack Packages
## Windows Build Tools
The xPack Windows Build Tools is a standalone Windows binary distribution of GNU make and a few of other tools required by the Eclipse Embedded CDT (formerly GNU MCU/ARM Eclipse) project, but the binaries can also be used in generic build environments.
## OpenOCD
Open On-Chip Debugger (OpenOCD) is a free, open-source project that aims to provide debugging, in-system programming, and boundary scan using a debug adapter. The adapter is a hardware module that provides the right signals for the target to understand
## QEMU
The xPack QEMU Arm is a standalone cross-platform binary distribution of QEMU, with several extensions for Arm Cortex-M devices.
## Components used in the project
## STM32F4O7VG Microcontroller board
The STM32F407 Kit takes advantage of the high-performance STM32F407 microcontrollers' capabilities to make it simple for users to create audio-based applications.It comes with an ST-LINK embedded debug tool, an ST-MEMS digital accelerometer, a digital microphone, an audio DAC with integrated class D speaker driver, LEDs, pushbuttons, and a USB OTG micro-AB connector.Ethernet connectivity, an LCD display, and other features have been added to the STM32F4 DISCOVERY kit. The STM32F405xx and STM32F407xx families are built around the high-performance Arm® Cortex®-M4 32-bit RISC core, which runs at up to 168 MHz.
## Features of STM32F407VG Microcontroller
USB ST-LINK with three separate interfaces and re-enumeration capability.
Large-scale storage (with new order code only).
Board power is supplied through USB or an external 5 V supply source.
16-bit and 32-bit timers.
Up to 2x 12-bit DAC.
External memory controller.
In a LQFP100 package, the STM32F407VGT6 microcontroller has a 32-bit ARM Cortex-M4 with FPU core, 1-Mbyte Flash memory, and 192-Kbyte RAM.
## Uses of STM32F407VG Microcontroller
This Microcontroller is utilised in printing and scanning machines ,heat ventilation, air conditioning, and security systems.
This module can be found in a variety of household products.
## Working Principle
Assume that the automobile is the microcontroller(STM32F407VG). If the button is pressed , the first led (red) will turn on, Clicking again the wiper will starts , and the second led (blue) will turn on for a desired rate. If the button is pressed again , the third led (green) will turn on, and the wiper's speed will be increased in comparison to the previous one. The fourth press will turn on the fourth led (orange) , and the wiper speed will be increased in accordance with the previous one. The microcontroller (vehicle) is turned off after the fifth click of the button.
## Swot Analysis
## Strengths
Hands-Free Calling.
Improve safety by decreasing driver distraction.
Automatically detects rain and wipes the windows by moving the wiper.
## Weakness
The rain sensor-based system functions when water falls on the sensor directly.
Structural Inertia.
## Opportunities
Emerging New Markets.
Hands-free calling.

