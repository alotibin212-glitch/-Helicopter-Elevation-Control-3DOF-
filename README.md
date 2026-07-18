# 🚁 Helicopter Elevation Control (3DOF)

A MATLAB/Simulink implementation of a closed-loop PID controller with a prefilter designed to manage the elevation angle of a 3-Degree of Freedom (3DOF) laboratory helicopter. The system ensures robust tracking and disturbance rejection across five flight phases.

---

## 🔗 Project Resources
Access the project report and simulation models here:
[📁 Project Google Drive Folder](https://drive.google.com/drive/folders/1ojZODPyGyZSUJNpmLcbmEnfPZsU6m0DI)

---

## 🎯 System Objectives
The controller is designed to handle complex flight dynamics, including:
* Reference Tracking: Precise elevation control during take-off, ascending, cruising, and landing.
* Disturbance Rejection: Robust recovery from an injected 2-second motor shutdown at t=65s.
* Constraints Management: Handling actuator saturation ($\pm 10V$), sensor quantization, and parametric uncertainties.

---

## 🏗️ System Architecture
The following diagram illustrates the closed-loop system implemented in Simulink, featuring the PID controller and prefilter integration.

<img width="1302" height="432" alt="لقطة شاشة 2026-07-18 153154" src="https://github.com/user-attachments/assets/f7e2265d-a4ee-4b79-96c1-8522991fc0ac" />


---

## 📊 Performance Analysis
The simulation demonstrates stable tracking and rapid recovery from transient oscillations. The optimized performance cost function is J = 2.2230.

<img width="1920" height="979" alt="لقطة شاشة 2026-07-18 153216" src="https://github.com/user-attachments/assets/b084768a-fae3-4237-a359-675edef6b524" />

<img width="1920" height="938" alt="لقطة شاشة 2026-07-18 153037" src="https://github.com/user-attachments/assets/04dcd4bd-74e1-4c4d-850e-5fcac6bdc5f8" />

---

## 👤 Developer
* Eng. Norah Al-Qathami
