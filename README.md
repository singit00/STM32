# STM32
Writing drivers for STM32 GPIO, I2C, SPI, USART
The aim of this project is the following
- Develop peripheral drivers for you µC
- Learn Writing peripheral driver headers, prototyping APIs and implementation
- Learn Right ways of handling/configuring Interrupts for various peripherals
- Learn about Configuration/status/Control registers of various Peripherals
- Explore hidden secretes of MCU bus interfaces, clock sources, MCU clock configurations, etc

### Table of Contents
- [Development Board](#Development-Board)
- [Hardware & Software Requirements](#Hardware-&-Software-Requirements)
- [Set up Visual Studio Code for STM23 development](#Set-up-Visual-Studio-Code-for-STM23-development)
[Integrated Developement Environment (IDE)](#Integrated-Installation-Environment-(IDE))
<!-- - [Debugging](#Debugging) -->
<!-- - [MCU](#MCU) -->
<!-- - [MCU Memory Map](#MCU-Memory-Map) -->
<!-- - [MCU Bus Interfaces](#MCU-Bus-Interfaces) -->
<!-- - [MCU Clock Tree](#MCU Clock Tree) -->
<!-- - [MCU Vector Table](#MCU Vector Table) -->

### Development Board
### Hardware & Software Requirements
#### Set up Visual Studio Code for STM23 development
https://www.youtube.com/watch?v=i_gcCkjz8OM
https://www.youtube.com/watch?v=T5MBKtjZDtg
https://www.youtube.com/watch?v=aWMni01XGeI
### Integrated Developement Environment (IDE)
- IDE is a software that contains all the essential tools to develop, compile, link and debug your code. 
- In some cases, you may have to integrate compiler and debugger tools to the IDE manually.
- Throughout this course we we will be using Eclipse-based STM32CubeIDE which is developed by ST Microelectronics to write, compile, debug applications on STM32 ARM-based icrocontrollers. 
- [STM32CubeIDE](#https://www.st.com/en/development-tools/stm32cubeide.html) is an eclipse IDE with STM32 related customization.
   - Use STM32CubeIDE below v2.00 (recommended v1.9 or v1.9)
   - uszip the file and install stm32cubeide_2.2.0-Win-x86_64.exe in C:\ST\STM32CubeIDE_2.2.0

### documents 
- Download Datasheet of [STM32F407VG](https://www.st.com/en/microcontrollers-microprocessors/stm32f407vg.html)
    - Download the reference manual [RM0090](https://www.st.com/en/microcontrollers-microprocessors/stm32f407vg.html#documentation)

    - Download product specification [DS8626](https://www.st.com/en/microcontrollers-microprocessors/stm32f407vg.html#documentation)

    - Download product specification for µC [DB1421](https://www.st.com/en/evaluation-tools/stm32f4discovery.html#documentation)

    - Download user manual for µC [UM1472](https://www.st.com/en/evaluation-tools/stm32f4discovery.html#documentation)

    - Download schematic for µC [STM32f4DISCOVERY schematics](https://www.st.com/en/evaluation-tools/stm32f4discovery.html#documentation)


 ### Create project
 - Launch STM32CubeIDE </br>
 <!-- <img src="./2026-07-23_11h31_58.png" alt="drawing" width="200"/> -->

 ![](./2026-07-23_11h31_58.png){width=75%}

Debug configurations
1. Hello World (STLink-V2)
SWV (Serial Wire Viewer) and Printf
How are we going to see the message output

2. HelloWorld SemiHosting (OpenOCD)

<!-- ### License -->
 
This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.



