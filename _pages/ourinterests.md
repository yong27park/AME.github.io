---
layout: archive
title: "Our Interests"
permalink: /ourinterests/
author_profile: true
---

## 1. High-Precision Sensor Interfaces
 We are deeply interested in developing high-precision sensor interfaces systems, especially focusing on biomedical wearable sensors, and neural interfaces. An analog-front-ends (AFEs) which is one of the core circuit blocks that interfaces with our real environment mostly determines overall performance of the systems. Therefore, we aim to design energy efficient but high-performance at the same time AFEs to communicate better with our real world.
 
<details markdown="1">
<summary><b>A. Depth of Anesthesia Monitoring System</b></summary>

<br>

![DoA](/images/research_DoA.png)

✅ ***What We Want to Solve?***
- During operation, surgeon should monitor two depth of anesthesia (DoA) indices, MAC and BIS depending on anesthetics
- Therefore, they need two bulky devices are needed to determine DoA

✅ ***How We Solve?***
- We design high-precision neural recording AFE with large DC dynamic range for long-term EEG recording
- We develop a novel DoA index by employing deep neural network (DNN)

✅ ***Related Publications***
- A Real-Time Depth of Anesthesia Monitoring System Based on Deep Neural Network With Large EDO Tolerant EEG Analog Front-End in *IEEE TBioCAS’20*

</details>

<br>

<details markdown="1">
<summary><b>B. AFEs with High Input Impedance</b></summary>

<br>

![DPFL](/images/research_DPFL.png)

✅ ***What We Want to Solve?***
- Input impedance of AFE should be boosted to be compatible with high impedance of dry-electrodes

✅ ***How We Solve?***
- We develop a dual positive feedback loops (DPFLs) to boost the input impedance even with large parasitic capacitance on PCB (CP-EXT)
- Feedback factors of DPFLs can be auto-calibrated by the on-chip calibration engine

✅ ***Related Publications***
- A 3.8-μW/Ch, 15-GΩ Total Input Impedance Chopper Stabilized Amplifier with Dual Positive Feedback Loops and Auto-calibration Scheme in *IEEE VLSI’21*
- A 3.8-µW 1.5-NEF 15-GΩ Total Input Impedance Chopper Stabilized Amplifier With Auto-Calibrated Dual Positive Feedback in 110-nm CMOS in *IEEE JSSC’22*

</details>

<br>

<details markdown="1">
<summary><b>C. Two-Electrode Bio-potential Recording System</b></summary>

<br>

![CMI](/images/research_CMI.png)

✅ ***What We Want to Solve?***
- We want to remove reference electrode, thus making conventional 3-electrode recording as 2-electrode recording system

✅ ***How We Solve?***
- We extremely reduce common-mode input impedance by developing CMI-Follower circuit while separating Earth-GND and Chip-GND

✅ ***Related Publications***
- A 4.6μW 3.3-NEF Biopotential Amplifier with 133VPP Common-Mode Interference Tolerance and 102dB Total Common-Mode Rejection Ratio for Two-Electrode Recording System in *IEEE ISSCC’25*
- A 4.6 μW, 133-VPP Common-Mode Interference-Tolerant Biopotential Amplifier for Two-Electrode Recording System in 110-nm CMOS in *IEEE JSSC’25*

</details>

## 2. High-Performance Time-of-Flight Depth Imagers
 Time-of-Flight (ToF) image sensors are widely used in various consumer applications, such as robot vacuum cleaners, Face ID systems, and AR/VR devices. As these applications require reliable operation under diverse environmental conditions, improving the robustness of ToF imaging systems is essential. Our research specifically addresses two critical challenges: image degradation under strong background illumination and image distortion caused by device mismatches.


