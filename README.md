# Suryavadhani AVN

Final-year Electronics and Communication Engineering student at VIT Vellore, graduating May 2027. I work at the hardware–software boundary: digital design in Verilog, microcontroller firmware, and the compute and control systems behind autonomous vehicles.

[surya06ammu@gmail.com](mailto:surya06ammu@gmail.com) · [LinkedIn](https://www.linkedin.com/in/suryavadhani-ammu/)

---

## Focus areas

- **Digital design** — RTL in Verilog, simulation-based verification against test vectors, FPGA implementation.
- **Computer architecture** — HPC cluster architecture (CPU and GPU nodes, interconnect), and processors from 8-bit AVR and 8051 to ARM Cortex-M and NVIDIA Jetson.
- **Embedded systems** — interrupt-driven firmware, UART/I2C/SPI, board bring-up and hardware debugging.

## Selected work

**DES Block Cipher on FPGA** (October 2026)  
Full DES cipher in Verilog: 16 Feistel rounds, key schedule, and S-boxes, verified in Icarus Verilog against standard test vectors. S-DES deployed on a Vicharak Shrike Lite (Renesas ForgeFPGA with an RP2040 host), with an on-chip self-check confirming correct output.

**HPC Architecture Study — IIT Madras** (May–June 2025)  
Documented the architecture of the AQUA Supercluster (1.1 PFLOPS) and PARAM Rudra (3.1 PFLOPS): Xeon Gold CPU nodes, NVIDIA V100/A100 GPU nodes, and InfiniBand interconnect. Also built an ESP32 system monitoring data-centre rack temperatures ([IOT-temp-sense](https://github.com/SuryavadhaniAVN/IOT-temp-sense)).

**Autonomous Ground Vehicle — Vrischik Technologies LLP** (May–June 2026)  
Wrote interrupt-driven ATmega328P firmware that converts Pixhawk or RC-receiver PWM into BTS7960 H-bridge signals, and a multi-threaded Python autonomy stack on a Raspberry Pi 4B for GPS waypoint navigation. Traced a failure that destroyed both ESCs to a defective buck converter and rebuilt the motor stage around BTS7960 H-bridges.

**Autonomous Underwater Vehicle — Team VAUV, VIT Vellore** (April 2024–March 2026)  
Technical Lead of a 15-member team. Built the motion control stack on Pixhawk (ArduSub) through a Python MAVLink bridge ([AUV](https://github.com/SuryavadhaniAVN/AUV)), and worked on YOLOv8n gate detection running on a Jetson Orin Nano.

**ESP32 Heart-Rate Monitor** (April 2026)  
Modular C++ firmware with threshold-based anomaly detection, an I2C OLED display, and a self-hosted web dashboard.

**NXP Cup 2026**  
Lane-keeping and obstacle-avoidance logic for the team's autonomous buggy in ROS 2 and Gazebo.

## Skills

**Digital design** — Verilog, Icarus Verilog, FPGA (Renesas ForgeFPGA), combinational and sequential logic, FSMs, Cadence Virtuoso  
**Programming** — C, C++, Python, MATLAB, Bash  
**Processors and platforms** — ARM Cortex-M (STM32, RP2040), AVR (ATmega328P), 8051, ESP32, NVIDIA Jetson Orin Nano, Raspberry Pi, Linux  
**Interfaces** — UART, I2C, SPI, 1-Wire, PWM  
**Robotics** — ROS 2, ArduPilot, MAVLink, Gazebo, OpenCV, YOLO

## Looking for

A six-month internship starting December 2026 in digital design, computer architecture, or embedded systems.
