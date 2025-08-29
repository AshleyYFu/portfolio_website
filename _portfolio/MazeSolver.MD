---
title: "Pololu Line Tracker and Maze Solver Robot"
excerpt: "An ATmega32u4 powered robot that achieves precise line tracking and strategic maze solving."
header:
  teaser: assets/img/Maze_Solver1.jpg
   
---

# About
In this project, a Pololu 32u4 robot was programmed to track a course and solve a maze with optimized methods.

This was my gateway course to embedded systems. The robot was programmed using C and I worked with constraints of a low cost system, such as limited memory and battery life. Most importantly, I learned ways to debug, whether it's using a JTAG reading hexadecimals on registers or blinkers sparkling multiple colors. I experienced writing bare metal firmware for every peripheral part of the system, from motor drivers to IR sensors, leveraging my knowledge in timers and interrupts.

* **Line Tracking:** Bang Bang controller incorporating 5 IR sensors
* **Maze Solving:** Left Hand Rule and IR sensor status tunings


# Skills
* Microcontrollers (ATmega328p and Atmega32u4), registers, timers, interrupts, clock systems
* Microchip Studio
* Writing low-level firmware in C & Assembly
* Peripheral interfacing, such as SPI and GPIO communication with sensors.

# Demo Video
This video demonstrates the smooth and precise line tracking. 
<video controls src="/portfolio_website/assets/img/Maze_Solver_Demo.mp4" title="Title" width="400" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></video>

# Credits
**ECE 2218 Microcontrollers** Fall 2024 Lab Project

{% include gallery %}
