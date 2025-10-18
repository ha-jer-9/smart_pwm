# 🧩 Smart PWM Generator SoC with ReRAM-Based Pattern Storage for Automotive Applications 

### **Author:** Hadjer Bouyahiaoui   
### **Project Name:** Smart PWM Generator SoC  
### **Target Platform:** ChipFoundry Caravel SoC (SKY130)  
### **Category:** Edge Computing / Automotive / Medical Applications  
### **License:** Apache 2.0  

---

## 🧠 Project Overview

**Smart PWM Generator SoC** is a system that integrates **Non-Volatile Memory (NVM)** for persistent PWM pattern storage and instant-on operation.  

This design demonstrates how embedded NVM can enhance system reliability and enable energy-efficient, intelligent control in **automotive**, **medical**, and **edge computing** environments.  

At power-up, the SoC automatically retrieves pre-stored PWM duty cycles or waveform patterns from **BM Labs’ ReRAM IP** and drives the outputs accordingly — without requiring external firmware reload or volatile configuration memory.

This approach significantly **reduces initialization time**, **saves power**, and provides **robust recovery** after unexpected resets or power losses.

---

## ⚙️ System Architecture

![Abstract_architecture](../docs/smart_pwm_architecture.png)




