---
title: "A Wireless Personal Area Network Receiver Amplifier"
excerpt: "A multi-stage feedback amplifier for a wireless network receiver with 65 dB gain and 100 kHz–5.8 MHz bandwidth"
header:
  teaser: assets/img/PAN1.jpg
   
---

## About
![Figure 1. Complete Circuit Diagram.](/portfolio_website/assets/img/PAN3.jpg)
*Figure 1. Complete Circuit Diagram.*

As part of an advanced electronics design project, I developed a high-gain, wideband receiver amplifier for a wireless Personal Area Network (PAN) receiver system. The amplifier was architected as a four-stage design: a common-base input stage for precise impedance matching, cascoded gain stages stabilized by series–shunt feedback to achieve the required bandwidth, and an emitter-follower output stage for low output impedance. 

![Figure 2. Conceptual Design Block Diagram](/portfolio_website/assets/img/PAN1.jpg)
*Figure 2. Conceptual Design Block Diagram.*

Using LTspice simulations, I verified that the amplifier consistently delivered **65 dB ±1.5 dB** gain across the required bandwidth of **100 kHz–5.8 MHz**, consumed less than 12 mA from a 6 V supply, and maintained performance under ±50% transistor manufacture process variations. This project strengthened my ability to integrate analog circuit design principles with simulation-driven validation to meet strict specifications.

![Figure 3. Nominal Beta Bode Gain Plot.](/portfolio_website/assets/img/PAN2.jpg)
*Figure 3. Nominal Beta Bode Gain Plot.*

The total circuit costs **$11.64**.

**Table 1**. Amplifier Associated Costs Itemization

| Item                  | Amount   | Cost Per Unit     | Total Cost |
|-----------------------|----------|------------------|------------|
| 1% Tolerance Resistor | 19       | $0.10            | $1.90      |
| 1 μF Capacitor        | 11       | $0.20            | $2.20      |
| ZTX107 BJT            | 6        | $1.00            | $6.00      |
| Power Profit Penalty  | 10.22 mW | $0.15 per mW     | $1.54      |
| **Total Amplifier Cost** |          |                  | **$11.64** |


## Skills Acquired
* Designing and optimization of multi-staged analog amplifier circuit with feedback for gain stability
* Impedance matching and bandwidth control
* Circuit simulation, bode plots, Bill of Materials (BOM)

## Credits
**ECE 4380 Electronics II** Spring 2025 Group Project
