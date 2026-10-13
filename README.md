# AEROSIM FPV | 6-DoF Drone Flight Dynamics Simulator & Pilot Academy

[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-cyan?style=for-the-badge&logo=github)](https://tareq0001.github.io/AeroSim-FPV-Drone-Pilot/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

**AEROSIM FPV** is a browser-native 6-DoF rigid-body aerodynamics flight simulator and professional UAV pilot certification academy. It accurately models quadrotor dynamics, quaternion attitude integration, Dryden wind gusts, FPV racing gate courses, and dual virtual gimbals.

---

## ⚡ Core Avionics & Physics Systems

1. **6-DoF Rigid-Body Flight Dynamics:**
   - Newton-Euler equations of motion.
   - Motor thrust calculation: $T_i = C_T ho A (\Omega_i R)^2$.
   - Quad-X frame motor mixing matrix for Pitch, Roll, Yaw torque distribution.
   - Aerodynamic parasite drag ($C_D$) and ground effect ($IGE/OGE$) lift augmentation.

2. **Flight Controller Modes:**
   - **Acro (Rate) Mode:** Direct angular velocity PID control ($^{\circ}/\text{s}$) for extreme FPV racing maneuvers.
   - **Angle (Stabilize) Mode:** Closed-loop accelerometer self-leveling with maximum tilt limiters.
   - **GPS / Altitude Hold Mode:** Autonomous barometric hover and position hold.

3. **Multi-Input Pilot Interface:**
   - Virtual Mode 2 Dual Sticks (Left: Throttle/Yaw, Right: Pitch/Roll) with spring centering.
   - Keyboard control support (`W/S` Throttle, `A/D` Yaw, Arrow keys for Pitch/Roll).
   - Direct Web Gamepad API integration for USB/Bluetooth RC controllers.

4. **Avionics OSD HUD:**
   - Real-time Artificial Horizon with Pitch Ladder & Roll Pointer.
   - Airspeed (km/h), Barometric Altitude (m), Variometer ($m/s$), Battery Cell Voltage ($V$) and mAh consumption.

5. **Pilot Certification Academy:**
   - Hover Stability Challenge.
   - 3D Neon Pylon Gate Slalom Course with checkpoint tracking.
   - Motor-Out Emergency Recovery landing.
   - Mountain Wind Shear & Gust survival.

---

## 🚀 Live Demo

Launch the simulator: [https://tareq0001.github.io/AeroSim-FPV-Drone-Pilot/](https://tareq0001.github.io/AeroSim-FPV-Drone-Pilot/)

Developed by **Tareq Aboushi** (أ. طارق ابوعشي).
