# Kaiden Joon Ko
**Computer Engineering & Computer Science @ USC**
Building embedded systems and biomedical signal-processing tools.

[LinkedIn](https://linkedin.com/in/kaidenjoonko) • [Email](mailto:kjko@usc.edu)

---

## About

I'm an engineer working at the intersection of **embedded firmware**, **biomedical signal processing**, and **real-time hardware-software systems**. My projects span bare-metal MCU firmware, FPGA/HDL design, and Linux-based IoT for medical applications.

**Current focus:** Bare-metal firmware, FPGA design, biomedical DSP, safety-critical embedded systems

---

## Projects

### ICU Watch Monitor
**Real-time sepsis early-warning IoT system**

Streams MIMIC-III physiological signals over MQTT pub/sub to a Raspberry Pi for continuous patient telemetry. Integrates GPIO hardware for bedside alerts when vital-sign thresholds are crossed, with topic-based routing on a Mosquitto broker.

`Python` `MQTT` `Raspberry Pi` `Flask` `SQLite` `GPIO`
[View Repository →](https://github.com/kaidenjoonko/ICU_Watch_Monitor)

---

### Vehicle Speed Trap
**Bare-metal embedded firmware on AVR ATmega328P**

Speed-measurement system timing object transits between dual opto-sensors, with LCD readout, EEPROM-persisted limits, and servo dial output. Coordinates three hardware timers across 5 ISRs and uses integer-only fixed-point math to avoid floating-point on the 8-bit MCU.

`C` `AVR` `ATmega328P` `avr-gcc` `Make`
[View Repository →](https://github.com/kaidenjoonko/speed-trap)

---

### FPGA Stroop Reaction Game
**Real-time reaction-time measurement on Xilinx Nexys A7**

Interactive Stroop-effect reaction-time game in Verilog, with VGA graphics output and millisecond-resolution timing. Implements two-flop reset synchronization for metastability prevention and integrates 8 Verilog modules across multiple clock domains.

`Verilog` `Vivado` `QuestaSim` `Xilinx Nexys A7`
[View Repository →](https://github.com/kaidenjoonko/fpga-stroop)

---

### Vita Health
**Computer vision system for at-home medical guidance**

Real-time guidance for accurate blood pressure measurement using object detection and pose estimation. Trained a custom YOLOv8 model achieving 97% mAP on medical device detection, integrated with MediaPipe for pose-based feedback.

`Python` `YOLOv8` `MediaPipe` `PyTorch` `OpenCV`
[View Repository →](https://github.com/kaidenjoonko/vita)

---

## Experience

**Bioinformatics Research Intern** • USC Institute for Technology and Medical Systems
*August 2024 - Present*

- Engineered a Python DSP pipeline for multi-channel EEG acquisition across 100+ patients, applying epoching, baseline correction, and feature extraction to isolate stress biomarkers
- Designed feature extraction scripts targeting frequency-band power, improving downstream ML classification accuracy by 10%
- Built 5 Python data acquisition interfaces automating EEG collection and labeling, reducing manual processing time by 70%

**Generative AI Engineering Intern** • Chevron Corporation
*May 2025 - July 2025*

- Architected a multi-agent Generative AI system using Semantic Kernel to transform JSON datasets into modular Vue/Bootstrap UI components, accelerating dynamic UI development by 10x
- Designed a cross-agent validation algorithm scoring output consistency, eliminating malformed generations by 90%

**Machine Learning Research Intern** • UCLA Biomedical Artificial Intelligence Research Lab
*May 2024 - August 2024*

- Engineered an OCR pipeline (TensorFlow/Keras) achieving 99%+ accuracy on 400+ medical images to extract retinal biomarkers for early retinal cancer diagnosis
- Built image preprocessing using adaptive thresholding and binarization to improve OCR robustness on low-contrast scans

---

## Technical Skills

**Embedded & Hardware**
AVR (ATmega328P) • Xilinx FPGA (Nexys A7) • Raspberry Pi • ISRs • GPIO • SPI • I²C • UART • ADC • PWM • EEPROM • quadrature encoders • PCB bring-up

**Languages**
C • C++ • Python • Verilog • JavaScript/TypeScript

**Tools & Workflow**
Vivado • QuestaSim • avr-gcc • Make • oscilloscopes/multimeters • Git • Linux

**Signal Processing & ML**
DSP (epoching, baseline correction, feature extraction) • PyTorch • TensorFlow • OpenCV

---

## Research Interests

- Embedded firmware for medical devices and biomedical instrumentation
- FPGA/HDL design and digital signal processing
- Safety-critical and real-time systems
- Neural signal acquisition and brain-computer interfaces

---

## Recognition

- **HackSC 2025 Winner**
- **CURVE Research Fellowship** — USC
- **Asian Pacific Alumni Association Scholar**

---

*Open to research collaborations and technical discussions in embedded systems and medical device engineering.*
