# Suryavadhani AVN

Robotics & autonomous systems engineer, embedded at the core. I build vehicles that fly, drive, and dive — and I've broken (and fixed) all three.

Final-year ECE undergrad at VIT Vellore · Technical Lead, Team VAUV · ex-Autonomous Systems Intern, Vrischik Technologies

📫 [surya06ammu@gmail.com](mailto:surya06ammu@gmail.com) · [LinkedIn](https://www.linkedin.com/in/suryavadhani-ammu/)

---

## What I actually do

I work across the full autonomy stack — flight controller to onboard compute to motor driver — on real hardware, not just simulation. My comfort zone is the boundary layer: where ArduPilot/PX4 talks to ROS2, where MAVLink telemetry becomes navigation decisions, and where a burnt ESC teaches you more about power design than any datasheet.

Currently split across three vehicle platforms:

- **AUV** — Technical Lead, [Team VAUV](https://github.com/SuryavadhaniAVN/AUV), VIT's underwater vehicle team
- **UGV** — built a three-tier autonomous rover architecture during a 2026 internship at Vrischik Technologies
- **Ground buggy** — NXP Cup 2026, autonomous perception + mission logic on the B3RB platform

## Recent work

**Autonomous UGV — Vrischik Technologies (May–June 2026)**
Designed a three-tier architecture (Pixhawk 2.4.8/ArduRover → Raspberry Pi 4B → Arduino motor interface) with RC, autonomous GUIDED, and direct-test modes and safe fallback switching. Wrote a multi-threaded Python autonomy stack for haversine-based GPS waypoint navigation, telemetry parsing, and failsafe handling, plus a custom pyserial driver for an RPLidar A1M8 giving 8-sector obstacle avoidance. Diagnosed a buck-converter overvoltage failure that killed the original ESCs, then rebuilt the motor stage around BTS7960 drivers.

**AUV autonomy stack — Team VAUV (2024–2026)**
Redeveloped the ROS2/Nav2 autonomy stack with YOLOv8n/YOLOv11 gate detection and visual servoing on a Jetson Orin Nano — this qualified VAUV for AqUaVision 2.0 at IIT Madras. Built the motion control stack on PixHawk/ArduSub via PyMavlink, a modular ESC attachment system that cut assembly time by 60%, and a custom PDB with fused, quick-disconnect power isolation.

**NXP Cup 2026 — Autonomous Medical Response Challenge**
Computer vision pipeline for sign detection and lane tracking (perspective correction, color-space analysis, template classification) plus QR-based mission logic for intersection routing and patient/hospital identification, running on the ROS2 Nav2 stack in Gazebo.

## Skills

**Robotics & Autonomy** — ROS2, Nav2, MAVLink, MAVROS, Gazebo, QGroundControl, YOLO
**Flight/Ground Stacks** — ArduPilot, PX4, ArduSub, ArduRover, PyMavlink
**Embedded** — Jetson Orin Nano, Raspberry Pi, ESP32, Arduino, Embedded C (Keil), I2C, SPI, UART
**Hardware/PCB** — EasyEDA, Fusion360, Cadence Virtuoso, custom PCB/PDB design, battery systems (LiPo/Li-ion/LiFePO4)
**Software** — Python, MATLAB/Simulink, gRPC, Docker, NumPy/Pandas/Matplotlib

## Pinned work

- 🌊 **[AUV](https://github.com/SuryavadhaniAVN/AUV)** — ROS2 packages and autonomy stack for Team VAUV
- 🥄 **[Tremor-Stabilizing-Spoon](https://github.com/SuryavadhaniAVN/Tremor-Stabilizing-Spoon)** — self-stabilizing spoon with PID auto-tuning and 3D visualization for tremor patients
- 🌡️ **[IOT-temp-sense](https://github.com/SuryavadhaniAVN/IOT-temp-sense)** — ESP32-based data center temperature monitoring, IIT Madras internship

## Right now

Looking for a 6-month internship or full-time role in **robotics, autonomous systems, or embedded systems** — drone/UAV, autonomous ground vehicles, defense-tech, or space-tech preferred. If you're building something in that space, I'd genuinely like to talk.
