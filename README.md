# Serial Console with Temperature Detection

This is the final project from the course Embedded System 1. This project was a room temperature detection system in Assembly with 3 modes for collecting data: buffer mode, slow mode, and fast mode.

## Micro-Controller and Board Schema
<div align="center">
    <img style="height:100%;" src="">
    <img style="height:100%;" src="">
</div>

![Micro-Controller](https://lh3.googleusercontent.com/2YM9eAnCKZKu3L29WaXN30f6D5rZ8R5VwIrBzx-AmD5dy0rkrOYRIdfgaq0VozsqK6JgUwB-32hJ)
![Board Schema](https://lh3.googleusercontent.com/U9t8GxCB75mbFo-su5UJLCYOJ8IDMc1R17cr3QFBBBScInLaiSQwdWWoy9gRmjW6ra3CAKqgw-Ju)

The micro-controller of the embedded system is STM32F446RE, and the processor is ARM® Cortex®-M4 32-bit RISC core operating at a frequency of up to 180 MHz. Peripherals consists of:

* Keypad
* Buzzer
* IR Signal Receiver
* Analog-to-Digital Converter (ADC)
* LED lights
* LCD screen
* Temperature Detector.

## Build Instruction

System Workbench for STM32 is the great tool for building and deploy applications to STM32 micro-controllers. It can be downloaded from the [link](https://www.openstm32.org/Downloading+the+System+Workbench+for+STM32+installer?structure=Documentation). You can create the F446RE project, and copy code from the repo to the project and build it.

## How to use the system?

The Embedded System uses USART to interact with the console, so make sure the board is connected with your PC and use PuTTY or other terminal simulators to interract with the system.

In the final product, temperature samples are collected every 1s under fast mode or 10s under slow mode. All data will be printed when the buffer mode is toggled. Pressing ’h’ will show the system instruction.

## Screenshots
