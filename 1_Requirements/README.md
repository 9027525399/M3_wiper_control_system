# Requirements
# introduction
A windscreen wiper or windshield wiper or wiper blade is a device used to remove rain, snow, ice, washer fluid, water from a vehicle's front window.Current car wipers works on the principle of manual switching. The traditional wiper system requires driver's constant attention in adjusting the wiper speed. Traditional windshield wiper speed constantly varies according to time and vehicle’s speed which not only require driver’s attention but also causes a certain level of discomfort to the driver's vision and serves as a source of distraction which increases the risk of accidents.So,to offer comfort to the driver and essentially reduce the risk of accidents, an automatic rain sensing device has become a necessity, as they work to minimize the time of the driver.Wiper Control System is basic need in the vehicles. To develop a good wiper system some basic requirements should be fulfilled, so that one can develop a trust worthy, so that one can develop a trust worthy wiper control system. Because wiper protects the vehicle to meet an accident. Wiper helps the driver to easily view the traffic and road. Wiper wipes out all the dust, dew, fog, and water setteled on the wind screen as well as rear shield.
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
## 4W's & 1H( who,what.when,where,how,why)
## what
The operational speed of a vehicle wiper is controlled by a wiper speed control mechanism based on rain conditions. To generate, the control system incorporates a rain sensor (30) that detects rain conditions. The amplitude of an analogue signal depends on the detected rain conditions.
## WHY
To clean the windscreen clean enough to give adequate view at all times from the front and rear windshields of the car.Wiper cleans the windshield by removing oil, dust, moisture, and grime that have become attached to the glass.
## WHEN
The windshield wipers remove rain and snow from the windshield, while the headlights improve visibility at night.
## WHO
It is extremely important for drivers of any type of vehicle that require clear road visibility in the event of dust, snow, or rain.
## HOW
It is implemented using the STM32 microcontroller and once when the rain droplets fall on the windshield of the vehicle.
## WHERE
In general,car wipers are controlled by the stalk on the right side of the steering wheel.
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
## Threats
Once the board repaired cannot be replaced quickly.
Low Bargaining Power Buyers.
Highly REgulated Industry.
Econimical Crisis.


