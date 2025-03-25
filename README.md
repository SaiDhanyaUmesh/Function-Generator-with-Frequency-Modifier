
---

# **Function Generator with Frequency Modifier**  

## **Project Overview**  
This project involves the design and implementation of a **function generator with a frequency modifier**, capable of producing **square, sine, and triangular waveforms**. The circuit uses **LT1498CN8 quad operational amplifiers**, with a **diode-based sine wave shaper**. The output frequency is controlled by varying **resistor values**, ensuring a stable **frequency bandwidth**.  

A **Printed Circuit Board (PCB) layout** has been designed to enhance performance by minimizing noise and improving reliability.  

## **Objectives**  
- Develop a **function generator circuit** to generate **square, sine, and triangular waveforms**.  
- Achieve a **wide frequency bandwidth** by varying **resistor values**.  
- Design a **PCB layout** to enhance **signal stability** and minimize noise.  

## **Circuit Design**  
The circuit consists of three main sections:  
- **Square Wave Generator** (Schmitt Trigger Oscillator using LT1498CN8).  
- **Triangular Wave Generator** (Integrator circuit using LT1498CN8).  
- **Sine Wave Shaper** (Diode-based non-linear network for waveform smoothing).  

## **Simulation & Results**  
- **Simulation performed using MultiSim and LTSpice**.  
- **Transient Analysis** was conducted to verify waveform behavior.  
- **FFT Analysis** confirms waveform accuracy and expected frequency response.  
- **Observed Frequency Range:** 600 Hz – 36.8 kHz.  

## **PCB Design**  
The PCB layout was designed using **EasyEDA/KiCad**, ensuring minimal noise and signal distortion.  

## **Repository Structure**  
```
Function-Generator-Frequency-Modifier  
│── README.md  (This file)  
│── Images_Files  
│── Simulation_Files/  (MultiSim, LTSpice, etc.)  
│── Gerber_Files/  (For PCB fabrication)  
│── BOM.csv  (Bill of Materials)  
```  

## **Future Improvements**  
- Integrate **microcontroller-based digital control** for automated frequency selection.  
- Optimize **component selection** for higher frequency accuracy.  
- Improve **waveform shaping techniques** to reduce distortion.  

## **References**  
- [Function Generator Using Op-Amp 741](https://how2electronics.com/square-wave-generator-circuit-op-amp-741/)  
- [RC Integrator Circuit](https://www.electronics-tutorials.ws/rc/rc-integrator.html)  
- [Function Generator Theory - IIT Roorkee Virtual Labs](https://ae-iitr.vlabs.ac.in/exp/function-generator/theory.html)  

## **Download & Access**  
Project files, including simulation and Gerber files, can be accessed at:  
[Click here](https://drive.google.com/drive/folders/1LxoEmGl-gFpvz_uacbN8fMdgtFOEIMpj?usp=drive_link)  

---
