---
title: "Ferro Beats"
excerpt: "A personal ferrofluidic speaker system that combines wireless audio playback with dynamic visual output."
header:
  teaser: assets/img/ferro_beat2.jpg
   
---

## About
![Figure 1. Conceptual Design Block Diagram](/portfolio_website/assets/img/ferro_beat1.jpg)
*Figure 1. Conceptual Design Block Diagram*

Ferro Beats is a custom-designed ferrofluidic speaker system that transforms music into both sound and synchronized visual motion. By streaming audio wirelessly via Bluetooth, the device drives a conventional speaker for playback while simultaneously actuating ferrofluid through an electromagnet controlled by a high-power MOSFET. The result is an engaging, music-responsive multimedia experience that blends embedded systems engineering with interactive art form.

This project provided a low-cost, DIY-friendly alternative to commercial ferrofluid speakers. 

### Key Features
* **Custom MCU Module**: Designed a microcontroller board to coordinate sensor acquisition, SPI/ADC data processing, PWM control, and wireless UART communication.
* **Real-Time Sensing and Safety**: Used an LM35 temperature sensor and DRV5055 Hall-effect sensor, digitized with a 12-bit MCP3202 ADC, to monitor thermal and magnetic conditions for safe operation.
* **Audio + Actuation Pipeline**: Processed stereo Bluetooth audio through a PAM8430 amplifier; one channel drove a speaker, the other controlled ferrofluid motion via MOSFET switching and a boost converter.
* **Interactive Control**: Supported remote commands through Bluetooth (HC-05), enabling sensitivity tuning, visualization modes, and real-time system feedback.
* **PCB & Enclosure**: Completed a double-sided PCB design and integrated it into a custoom enclosure sized for desktop use.


![Figure 2](/portfolio_website/assets/img/ferro_beat3.jpg)
*Figure 2. PCB Layout.*

![Figure 3](/portfolio_website/assets/img/ferro_beat2.jpg)
*Figure 3. 3D PCB Rendering Using KiCad.*

## Skills Acquired
* Embedded system design (SPI, UART, PWM, ADC integration)
* PCB schematic layout under size constraints
* Analog/digital circuit design (signal conditioning, MOSFET drivers, boost converters)
* Safety monitoring and close-loop control with sensors
* Wireless communication and user I/O

## Credits
**ECE 4275 Microelectronic Systems** Spring 2025 Group Project
