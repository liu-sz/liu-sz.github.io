---
layout: page
title: Projects
permalink: /Projects/
---

### **CMOS IC Projects with Cadence**

#### **Transimpedance Amplifier (TIA)**
- Designed a TIA with a transconductance (gm)-boosted common-gate input stage, a cascode gain stage, and a common-drain output stage
- With Cin=1 pF, CL=2 pF, RL=10 kΩ, and T=27°C, achieved the following performance:
    - Low-frequency transimpedance gain >140 kΩ
    - Input resistance <250Ω 
    - 3dB Bandwidth >230MHz
    - Output swing >400mV
    - Power <500uW

![TIA](/assets/TIA.png){: width="500" } 

*TIA circuit*

#### **Operational Amplifier (op amp)**
- Designed an op amp with a differential pair input stage and a common-source gain stage
- With CL=2 pF, VDD=1.5V, T=27°C, β=0.5, and a common-mode voltage (Vcm) of 0V, achieved the following performance:
    - Open loop gain >770 V/V
    - Phase margin >70°
    - Unity loop gain frequency >200 MHz
    - Slew rate >100V/us
    - Output swing >1V
    - Power <400uW
    - Input offset <1mV
- Achieved high yield with Monte Carlo analysis at T=0°C, 27°C, and 100°C, and Vcm = -0.1V, 0V, 0.1V
- Laid out op amp utilizing a common-centroid configuration and dummy cells to reduce mismatches

![Op Amp](/assets/op_amp.png){: width="500" } 

*Op amp circuit*

#### **Static Random Access Memory (SRAM)**
- Designed and laid out an SRAM with a capacity of 256 16-bit words and a pre-layout read/write cycle time < 25 FO4 
- Used column multiplexing, pre-decoding, and a cross layout topology to reduce cycle time

### **Other Projects**

#### [Mapping the Life of Monet with ArcGIS StoryMaps](https://storymaps.arcgis.com/stories/9c3667131970423ebbedc86a134475e5)
<a title="Claude Monet
, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Monet_-_Impression,_Sunrise.jpg"><img width="256" alt="Monet - Impression, Sunrise" src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/59/Monet_-_Impression%2C_Sunrise.jpg/512px-Monet_-_Impression%2C_Sunrise.jpg"></a>

*Impression, Sunrise* by Claude Monet, Public domain, via Wikimedia Commons
