---
id: 578
title: SCBEVO-8
date: '2015-10-29T13:26:37+00:00'
author: bdriller
layout: page
guid: 'http://www.4stars-es.com/?page_id=578'
video_type:
    - '#NONE#'
---

## <span style="color: #ff6600;">***System Control Board (SCBEVO-8)***</span>

#### The SCBEVO-8 is a 12 axis motion controller for use in Flying Probe Testers for PCBs.

The module is perfectly driven and controlled by the FourStars-ES ProbeStar Software.

#### **The main function of the SCB are:**

- Generation of pulse/direction signals for Servo-Amplifiers and Stepper-Motor-Controllers
- Handling of axis end- and reference-switches
- Test-Probe compression control

[![](http://www.4stars-es.com/wp-content/uploads/2015/10/SCB-8_LQ.jpg "GPA_LQ")](http://www.4stars-es.com/wp-content/uploads/2015/10/SCB-8_LQ.jpg)

<span style="color: #ff0000;"> SCBEVO-8 (modified picture sharpness to save IP)</span>

#### **The module contains:**

- Power connector for single 24V DC supply
- Local voltage regulators
- Analog components (converters, amplifiers, etc. )
- High performance (Altera) FPGA for real time calculation of speed profiles and pulse generation
- FPGA integrated soft cores for smart data handling
- Interface to Motor amplifiers
- Synchronization port to measuring devices
- USB-Interface to the controlling PC

#### **Specification:**

- *Programmable parameter each axis:*
    - stepsize (typ. 1 µm)
    - distance (steps)
    - max. speed forward/backward (steps/s)
    - acceleration forward/backward/z-detect (steps/s²)
    - jerk-suppression (steps/s³)
    - etc.
- *Field upgradable firmware for CPU and FPGA*