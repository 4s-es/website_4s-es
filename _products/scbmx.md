---
title: SCBMX
date: '2022-02-02T09:22:54+00:00'
author: bdriller
product_code: SCBMX
layout: product
---
## <span style="color: #ff6600;">***System Control Board (SCBMX)***</span>

The **SCBMX** is a twenty eight axis, eight head motion controller for Flying Probe Testers.  
It is designed for use in the Micronic Innovation Series test systems.  
The module is perfectly driven and controlled by the FourStars-ES [OctaStar Software]({{site.url }}{{site.baseurl }}products/octastar-software/).

#### **The main functions of the SCBMX are:**

- Generation of signals for Servo-Amplifiers and Motor-Controllers
- Handling of axis end- and reference-switches
- Handling of Encoder signals
- Test-Probe compression control

[![]({{site.url }}{{site.baseurl }}assets/wp-content/uploads/2022/02/ScbMx-1024x368.jpg "GPA_LQ")]({{site.url }}{{site.baseurl }}assets/wp-content/uploads/2022/02/ScbMx-1024x368.jpg)

<span style="color: #ff0000;"> SCBMX (modified picture sharpness to save IP)</span>

#### **The module contains:**

- Power connector for single 24V DC supply
- Local voltage regulators
- Analog components (converters, amplifiers, etc. )
- SoC (System-on-Chip) containing 
    - high performance FPGA for real time calculation of speed profiles, synchronization etc.
    - ARM-based hard Processor for smart data handling and communcation
- Interface to Motor amplifiers
- Synchronization port to measuring devices
- Gigabit-Ethernet-Interface to the controlling FPT-PC

#### **Specification:**

- *Programmable parameter each axis:*
    - stepsize (typ. 1 µm)
    - distance (steps)
    - max. speed forward/backward (steps/s)
    - acceleration forward/backward/z-detect (steps/s²)
    - jerk-suppression (steps/s³)
    - etc.
- *Field upgradable firmware for SoC (Processor and FPGA)*
