# 🤖 Self-Balancing Robot Using PID Control

A two-wheeled self-balancing robot designed and implemented as part of **NANENG 212 – Applied Digital Control** at **Zewail City of Science and Technology**.

The project combines **control theory, system modeling, sensor fusion, embedded systems, and real-time feedback control** to stabilize an inherently unstable inverted pendulum system.

---

## 📸 Project Overview

### Hardware Implementation

![Robot Construction](robot.jpg)

### MATLAB Pole-Zero Analysis

![Pole Zero Map](pole-zero.png)

### System Response

![Response Analysis](response.png)

---

## 🎯 Project Objective

Design and implement a self-balancing robot capable of maintaining an upright position using:

- PID Control
- IMU Sensor Fusion
- Real-Time Feedback
- PWM Motor Control
- Dynamic System Modeling

The robot continuously measures its tilt angle, calculates the balance error, and adjusts motor speed to maintain stability.

---

## 🧠 Engineering Concepts

- Inverted Pendulum Dynamics
- PID Control Design
- State-Space Modeling
- Pole-Zero Analysis
- Stability Analysis
- Sensor Fusion
- Feedback Control Systems
- DC Motor Modeling
- MATLAB Simulation

---

## ⚙️ System Architecture

```text
Setpoint
    ↓
Error Calculation
    ↓
PID Controller
    ↓
Motor Driver
    ↓
DC Motors
    ↓
Robot Dynamics
    ↓
IMU Feedback
    ↺
```

---

## 🛠 Tools & Technologies

- MATLAB
- Control System Toolbox
- PID Controller Design
- IMU Sensors
- DC Motors
- PWM Control
- Embedded Hardware

---

## 📊 Key Outcomes

- Developed a mathematical model of a self-balancing robot.
- Implemented PID-based stabilization.
- Performed stability analysis using pole-zero techniques.
- Analyzed system response and controller performance.
- Successfully demonstrated real-time balancing behavior.

---

## 📂 Repository Contents

```text
Self-Balancing-Robot/
│
├── README.md
├── Report.pdf
├── MATLAB_Model.slx
├── robot.jpg
├── pole-zero.png
└── response.png
```

---

## 🎓 Course Information

**Course:** NANENG 212 – Applied Digital Control  
**University:** Zewail City of Science and Technology  
**Semester:** Spring 2026

---

## 👥 Attribution

This repository documents a collaborative undergraduate academic project. The GitHub repository is maintained individually as part of a professional engineering portfolio.
