---
title: "Your Dawg"
excerpt: "A real-time robotics gesture recognition and response system mimicking a well-trained pet dog."
header:
  teaser: assets/img/Your_Dawg1.jpg
gallery:
  - image_path: assets/img/Your_Dawg1.jpg
  - image_path: assets/img/Your_Dawg2.jpg
   
---

## About
The project “Your Dawg” implements a real-time gesture recognition and response system for a robotics
platform using Raspberry Pi 5 encapsulated in a Turbo Pi robot. The project was inspired by human
interactions with their pet dogs that can understand commands and perform actions. Using TensorFlow 
and a pi camera module, we built a computer vision model that detects and classify hand gestures.
The system thus can interpret human input and triggers corresponding hardware-based reactions, 
such as moving motors, activating LEDs, or playing tones through buzzer.

The project is built with modular Python scripts that run in parallel and communicate using ZeroMQ,
making it responsive and extensible. The primary goal is to create an intuitive, interactive interface
between humans and a “robot dog”, with each gesture mapped to a unique sequence of hardware actions.

* **Gesture Recognition** Your Dawg can recognize three hand gestures: Rock n Roll, Bark, and Circle
* **Hand Tracking** Your Dawg can detect and track your moving hand, panning and tilting its camera head in the same motion as your hand! 
* **Real Time Operating Systems** The modular architecture is built using multithreaded Python and coordinated through a ZeroMQ-base pub/sub model. Three Raspberry Pi cores are utilized to enable true parallelism between gesture recognition and hand tracking. This lays the groundwork for future expansion. 

## Skills Acquired
* Multithreading and parallel processing
* Real time operating systems (RTOS)
* Computer vision
* Open source and code versioning / source control

# Demo Video
<video controls src="../assets/img/Your_Dawg_Demo.mp4" title="Title" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></video>

## Credits
**ECE 4375 Embedded Systems** Spring 2025 Group Project

{% include gallery %}
