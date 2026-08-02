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

<details markdown="1">
<summary><b>A. Indirect Time-of-Flight Imager with High Background Light Tolerance </b></summary>

<br>

![Blossom](/images/research_Blossom.png)

✅ ***What We Want to Solve?***
- High background light from the sunlight can saturate the pixel causing depth image distortions
- We want to enhance the dynamic range of each pixel without compromising image quality

✅ ***How We Solve?***
- We employ in-pixel adaptive delta-sigma circuit to remove only common-mode charge, thus enhance the dynamic range
- Pixel-level floating diffusion swapping enhances the depth linearity


✅ ***Related Publications***
- A 160×120 Indirect Time-of-Flight Sensor with Pixel-Level Adaptive ΔΣ-Operations for Background Light Cancellation in *IEEE A-SSCC’23*
- An Indirect ToF Sensor With In-Pixel Adaptive ΔΣ-Scheme for Background Light Rejection and Floating Diffusion Mismatch Cancellation in *IEEE JSSC’25*

</details>

<br>

<details markdown="1">
<summary><b>B. Indirect Time-of-Flight Imager with Motion Artifact and Mismatch Tolerance</b></summary>

<br>

![Tetra](/images/research_Tetra.png)

✅ ***What We Want to Solve?***
- Conventionally, we need two frame images to create one depth image, causing motion artifact
- Floating diffusion(FD) mismatch creates significant non-linearity distorting depth images

✅ ***How We Solve?***
- We develop tetra-pixel architecture to provide one depth image in a single shot
- FD mismatches can be mitigated by simple interpolation technique

✅ ***Related Publications***
- An Indirect Time-of-Flight Sensor with Adaptive Multiple Sampling for High Depth Precision in *IEEE VLSI’22*
- An Indirect Time-of-Flight Sensor With Tetra-Pixel Architecture Calibrating Tap Mismatch in a Single Frame in *IEEE SSC-L’22*

</details>

## 3. High-Speed Optical Interconnects
 Silicon photonics has emerged as a key technology for overcoming the bandwidth and energy limitations of conventional electrical interconnects in AI and high-performance computing (HPC) systems. Our research will focus on developing energy-efficient and high-speed electrical integrated circuits (EICs). In particular, since the performance of photonic devices is highly sensitive to temperature variations, we aim to develop intelligent temperature control units (TCUs) that compensate for large thermal drifts and stabilize photonic devices, enabling robust and reliable optical interconnects

<details markdown="1">
<summary><b>A. Temperature Stabilizer for Photonic Devices </b></summary>

<br>

![Si](/AME.github.io/images/research_Si2.png)

✅ ***What We Want to Solve?***
- Large temperature variations during data transmission induce resonant wavelength shifts, leading to severe bit-error-rate (BER) degradation.
- Precise resonant wavelength calibration is required to realize dense wavelength division multiplexing (DWDM).

✅ ***How We Solve?***
- We develop temperature control units (TCUs) to precisely compensate for temperature-induced resonant wavelength shifts in microring modulators.
- Additionally, thermal control is performed seamlessly in the background without degrading BER or data transfer rates.


✅ ***Related Publications***
- We are working on it!

</details>

