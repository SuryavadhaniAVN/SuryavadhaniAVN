# Suryavadhani AVN

Final-year Electronics and Communication Engineering student at VIT Vellore, graduating May 2027. I work on embedded systems and robotics hardware: microcontroller firmware, power and motor electronics, and the software that ties a vehicle together, with digital design work in Verilog and FPGAs.

[surya06ammu@gmail.com](mailto:surya06ammu@gmail.com) · [LinkedIn](https://www.linkedin.com/in/suryavadhani-ammu/)

---

## Focus areas

- **Embedded systems** — interrupt-driven firmware on AVR, ARM Cortex-M, and ESP32; UART/I2C/SPI; board bring-up and hardware debugging.
- **Robotics and autonomous vehicles** — ArduPilot and MAVLink integration, ROS 2, and the onboard compute and control stack for ground and underwater vehicles.
- **Digital design** — RTL in Verilog, simulation-based verification against test vectors, and FPGA implementation.

## Selected work

**Autonomous Ground Vehicle — Vrischik Technologies LLP** (May–June 2026)  
Wrote interrupt-driven ATmega328P firmware that converts Pixhawk or RC-receiver PWM into BTS7960 H-bridge signals, and a multi-threaded Python autonomy stack on a Raspberry Pi 4B for GPS waypoint navigation. Traced a failure that destroyed both ESCs to a defective buck converter and rebuilt the motor stage around BTS7960 H-bridges.

**Autonomous Underwater Vehicle — Team VAUV, VIT Vellore** (April 2024–March 2026)  
Technical Lead of a 15-member team. Built the motion control stack on Pixhawk (ArduSub) through a Python MAVLink bridge ([AUV](https://github.com/SuryavadhaniAVN/AUV)), and worked on YOLOv8n gate detection running on a Jetson Orin Nano.

**DES Block Cipher on FPGA** (October 2026)  
Full DES cipher in Verilog: 16 Feistel rounds, key schedule, and S-boxes, verified in Icarus Verilog against standard test vectors. S-DES deployed on a Vicharak Shrike Lite (Renesas ForgeFPGA with an RP2040 host), with an on-chip self-check confirming correct output.

**HPC Architecture Study — IIT Madras** (May–June 2025)  
Documented the architecture of the AQUA Supercluster (1.1 PFLOPS) and PARAM Rudra (3.1 PFLOPS): Xeon Gold CPU nodes, NVIDIA V100/A100 GPU nodes, and InfiniBand interconnect. Also built an ESP32 system monitoring data-centre rack temperatures ([IOT-temp-sense](https://github.com/SuryavadhaniAVN/IOT-temp-sense)).

**ESP32 Heart-Rate Monitor** (April 2026)  
Modular C++ firmware with threshold-based anomaly detection, an I2C OLED display, and a self-hosted web dashboard.

**NXP Cup 2026**  
Lane-keeping and obstacle-avoidance logic for the team's autonomous buggy in ROS 2 and Gazebo.

## Skills

**Embedded** — ARM Cortex-M (STM32, RP2040), AVR (ATmega328P), 8051, ESP32, Raspberry Pi, NVIDIA Jetson Orin Nano; UART, I2C, SPI, 1-Wire, PWM  
**Programming** — C, C++, Python, MATLAB, Bash, Linux  
**Robotics** — ROS 2, ArduPilot, MAVLink, Gazebo, OpenCV, YOLO  
**Digital design** — Verilog, Icarus Verilog, FPGA (Renesas ForgeFPGA), combinational and sequential logic, FSMs, Cadence Virtuoso

## Looking for

A six-month internship starting December 2026 in embedded systems, hardware, or robotics.
