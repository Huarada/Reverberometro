# Comb Filter Simulation — LabVIEW

This project implements a **Comb Filter** simulation using **LabVIEW**.  
The program is designed to demonstrate digital signal processing (DSP) concepts and the behavior of comb filters, which are widely used in **audio effects, echo suppression, and spectral shaping**.

> Main program: `filtro_Instru.vi`

---

## Table of Contents

- [Overview](#overview)  
- [What is a Comb Filter?](#what-is-a-comb-filter)  
- [Features](#features)  
- [How to Run](#how-to-run)  
- [Program Structure](#program-structure)  
- [Applications](#applications)  
- [Repository Structure](#repository-structure)  
- [Roadmap](#roadmap)  
- [License](#license)

---

## Overview

The goal of this project is to simulate the effect of a **comb filter** in the frequency and time domain.  
The implementation is built in **LabVIEW**, leveraging its visual programming paradigm for signal generation, processing, and visualization.

This project was created to strengthen understanding of **digital filters** and to serve as an educational resource for DSP-related courses and experiments.

---

## What is a Comb Filter?

A comb filter is a signal processing filter characterized by a frequency response that has a series of regularly spaced notches or peaks, resembling the teeth of a comb.  
It can be implemented in two main forms:

- **Feedforward comb filter**: adds a delayed version of the signal to itself.  
- **Feedback comb filter**: feeds the delayed output back into the input.  

Applications include:  
- Echo and reverb effects in audio processing.  
- Delay-based effects in music production.  
- Spectral shaping in communication systems.  
- Speech enhancement and noise reduction.

---

## Features

- Simulation of **feedforward and feedback comb filters**.  
- Adjustable parameters:  
  - Delay length  
  - Gain/attenuation factor  
  - Sampling frequency  
- Real-time waveform and spectrum visualization.  
- Easy-to-use graphical interface in LabVIEW.  

---

## How to Run

1. Open **LabVIEW** (version 2020 or later recommended).  
2. Load the file `filtro_Instru.vi`.  
3. Run the VI (`▶` button in LabVIEW).  
4. Use the front panel controls to:  
   - Select delay values.  
   - Adjust feedback/feedforward coefficients.  
   - Visualize the filtered output in **time domain** and **frequency domain**.  

---

## Program Structure

- **Front Panel**:  
  - User interface for parameter tuning (delay, gain, input signal).  
  - Graphs for signal visualization.  

- **Block Diagram**:  
  - Implements comb filter equations using LabVIEW signal processing blocks.  
  - Includes loops for continuous signal generation and real-time updates.  

---

## Applications

- Educational tool for understanding DSP fundamentals.  
- Testing audio processing effects.  
- Demonstrating resonance and filtering behavior.  
- Prototype for speech/audio enhancement systems.  

---

## Repository Structure

```
.
├── filtro_Instru.vi       # Main LabVIEW VI (comb filter simulation)
└── README.md              # Documentation
```

---

## Roadmap

- Extend to include **IIR and FIR filter comparisons**.  
- Add **export functionality** for filtered signals (WAV format).  
- Integrate with **MATLAB/Octave** for cross-validation of results.  
- Add support for **multi-channel (stereo) signals**.  

---

## License

Choose one depending on your goals:  
- **MIT** — permissive, simple.  
- **Apache 2.0** — better for enterprise adoption.  

---

### Recruiter’s note

This project demonstrates ability to:  
- Work with **DSP concepts** and translate them into practical implementations.  
- Use **LabVIEW** for simulation and visualization of real-time systems.  
- Document and explain signal processing systems in a way that bridges academia and industry.  

It reflects strong foundations in **digital signal processing, control systems, and applied software engineering**.
