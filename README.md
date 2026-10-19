## Óscar García Redondo 

**Biomedical Engineering student · Embedded firmware for medical devices**

I build the full chain of a medical device, from the analog front-end that reads a biosignal, through the real-time firmware that acquires it, to the model that interprets it. I care about systems that are not just working, but *measured*: deterministic, predictable, and validated on hardware rather than on a slide.

📍 Madrid, Spain · Final-year BSc in Biomedical Engineering (UAM)

---

### 🔧 Personal Skills

**Embedded & Firmware**
`C` · `ARM Cortex-M4 / M7` · `STM32 (L4 / H7)` · `FreeRTOS` · `TIM→ADC→DMA` · `Interrupts / NVIC` · real-time state machines

**Signal & Embedded ML**
`Python` · `DSP` · `int8 quantisation` · `TFLite-Micro` · `CMSIS-NN` · `X-CUBE-AI` · on-device inference

**Analog & Hardware**
biopotential front-end design · instrumentation amplifiers · galvanic isolation · active filtering · sEMG/EMG acquisition · oscilloscope debugging

**Currently learning** → MISRA C:2012 · medical-device software lifecycle (IEC 62304 / ISO 14971)

---

### 🚀 Projects

**🩸 [TinyML at the Edge — Blood Cell Classification on STM32](https://github.com/oscarcolme10/tinyml-medmnist-stm32l4)**
An int8 CNN deployed on a Cortex-M4 (STM32L476RG) within a 128 kB RAM budget — 92% accuracy at 174 ms/inference, measured on hardware. No accelerator, no cloud, no external RAM. A study in taking a model from training through quantisation to a real embedded target.

**🦾 Myoelectric Prosthetic Hand — Real-Time sEMG Gesture Recognition** *(in progress — thesis)*
End-to-end biosignal system, electrode to actuator: a 4-channel sEMG analog front-end I designed and bench-validated myself, plus deterministic acquisition and gesture-classification firmware migrating to an STM32H7 under FreeRTOS. *Repository coming once the hardware measurements are in.*

---

### 🧭 What I'm about

I'm drawn to the point where hardware meets software, the messy, real part where a signal has to be conditioned, sampled deterministically, and turned into a reliable decision, all on a resource-constrained microcontroller. My goal is to grow into firmware development for active medical devices: prosthetics, neurotechnology, medical robotics.

Outside the bench: futsal, and coaching a youth team taught me more about leading under pressure than any lab did.

---

### 📫 Reach me

[LinkedIn](https://www.linkedin.com/in/oscargarciared) · oscar.garcia.redondo.2304@gmail.com
