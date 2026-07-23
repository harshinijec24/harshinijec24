# Hi, I'm Harshini 👋

ECE undergrad at RV College of Engineering, Bangalore, building at the intersection of embedded systems, robotics, and signal processing.

- 🔭 Currently working on **RUDRAN** — a modular 4-wheel differential drive robotic platform with TinyML voice control and autonomous navigation
- 🌱 Exploring FPGA-based DSP/edge-AI pipelines and wireless embedded communication
- 🛠️ Comfortable across the stack: RTL design → firmware → Python tooling → CAD
- 📫 Reach me at **kumarharshini13@gmail.com** | [LinkedIn](https://www.linkedin.com/in/harshinijayakumar-215216319)

---

## 🧰 Technical Skills

**Hardware & Embedded Systems:** Raspberry Pi 3, FPGA, Arduino, PYNQ (Zynq-7000), STM32, ESP32
**HDL & FPGA Tools:** Verilog, VHDL, Xilinx Vivado
**Programming:** Python, SQL
**Libraries & Frameworks:** scikit-learn, Flask, Scapy, OpenCV, pandas, matplotlib, Tkinter, pymavlink
**Tools:** ImageJ, LTSpice, KiCad, SolidWorks, Mission Planner, MS Office
**Domains:** Embedded Systems, FPGA/DSP Design, Robotics, Analog Circuit Design, Wireless Security, Machine Learning

---

## 🚀 Projects

### [RUDRAN — Modular 4-Wheel Differential Drive Robotic Platform](#)
`ESP32` `TinyML` `L298N` `Embedded Systems` `Autonomous Navigation`
A modular intelligent robotic platform built around an ESP32-WROOM-32, driving four TT DC motors via a single L298N for differential steering. Supports both Manual (RC) and Autonomous modes, selectable via TinyML voice keyword spotting, a Wi-Fi dashboard, or a physical backup switch. Autonomous mode uses an HC-SR04 ultrasonic sensor and dual IR sensors for real-time obstacle detection and path selection. Implements a hierarchical safety-first control architecture where obstacle avoidance always overrides manual/voice commands. Custom 3D-printed chassis on a 2S Li-ion + BMS power system. Designed as Phase 1 of a scalable platform, with RUDRAN Mk-II planned to add onboard vision and person classification without any mechanical redesign.

### [Connected Drone-Rover Surveillance System using MAVLink](#)
`STM32F103C8T6` `nRF24L01` `DRV8833` `Python (pymavlink)`
Low-cost embedded UAV-UGV communication pipeline converting real-time MAVLink drone attitude telemetry into autonomous rover motion commands. Five-stage architecture: Mission Planner SITL → Python (pymavlink) → STM32 → nRF24L01 → DRV8833. Deterministic command-mapping algorithm with ±5° dead zone, firmware-level payload validation to reject noise-induced false actuation.

### [Dual-Path FPGA-Based Image Processing System](https://github.com/harshinijec24/dualpath-fpga-image-processing)
`Verilog HDL (RTL)` `Vivado` `Python` `OpenCV`
Dual-path FPGA architecture balancing accuracy and hardware efficiency for real-time edge AI. Hand-coded RTL Verilog 3×3 convolution + ReLU for CNN-based feature extraction, alongside a lightweight pixel-difference/threshold inference pipeline for low-latency binary outputs. Python-based pre/post-processing validated via Vivado simulation and testbenches.

### [Real-Time Edge Detection using Sobel and Canny on PYNQ-Z2](#)
`Python` `OpenCV` `NumPy` `ARM Cortex-A9`
Real-time embedded computer vision application comparing Sobel and Canny edge detection for video processing, with a full frame-by-frame pipeline (acquisition, grayscale conversion, resizing) and an interactive dashboard for simultaneous output comparison — optimized for low-latency embedded execution.

### [Audio Spectrum Analyzer on PYNQ-Z2](#)
`Python` `Custom FFT Pipeline` `Matplotlib` `ARM Cortex-A9`
Embedded real-time frequency analyzer built around a custom 256-point FFT pipeline (no external DSP frameworks). End-to-end signal chain: audio parsing → frame extraction → windowing → FFT → magnitude calculation → smoothing → peak tracking, visualized via an interactive Matplotlib dashboard (waveform, spectrum, spectrogram).

### [FPGA-Based Low-Pass FIR Filter on PYNQ (Zynq SoC)](#)
`Verilog/VHDL` `Xilinx Vivado` `DSP`
FIR low-pass filter designed in HDL, deployed on PYNQ (Zynq-7000 SoC), with frequency response validated on hardware.

### [Full-Wave Precision Rectifier for Low-Voltage Signals](#)
`Op-Amps (µA741/LM358)` `Analog Design`
Active precision rectifier eliminating diode forward-voltage-drop errors, verified via simulation and oscilloscope testing. PCB layout designed in KiCad with fabrication-ready Gerber outputs.

### [Wi-Fi Intruder Detection on Raspberry Pi 3](#)
`Python` `Scapy` `Flask` `Embedded Linux`
Passive 802.11 probe sniffing with RSSI-based proximity estimation, whitelist filtering, and event-driven camera triggering for intrusion validation.

### [Electrospun Nanofiber Optimization using Machine Learning](#)
`Python` `Random Forest` `ImageJ`
Random Forest regression model for fiber diameter prediction, used to optimize electrospinning parameters for uniform, bead-free nanofiber formation.

### [YOLOv8 Vehicle Detection](#)
`Python` `Ultralytics YOLOv8`
Vehicle detection model trained on annotated datasets, achieving high detection accuracy through iterative training and evaluation.

### [Machine Learning-Based Player Recruitment System](#)
`Python` `scikit-learn` `Flask`
Supervised and clustering models for data-driven player evaluation, deployed as an analytics engine with dashboard visualization.

---

## 🏆 Certifications & Achievements

- 🥉 3rd Place — Line Follower Bot, Ascent (Builders TechFest, Scaler School of Technology), May 2026
- Embedded System Design with ARM — NPTEL, IIT Kharagpur (Jan–Mar 2025)
- Problem Solving (Basic) — HackerRank (2025)
- Semiconductor Manufacturing Workshop — IISc Bangalore (2025)
- 🥈 2nd Place — Hult Prize RVCE Entrepreneurial Competition (Qualified for national round)

---

## 📊 GitHub Stats

![Harshini's GitHub stats](https://github-readme-stats.vercel.app/api?username=harshinijec24&show_icons=true&theme=default&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=harshinijec24&layout=compact&hide_border=true)

---

📫 **kumarharshini13@gmail.com** · [LinkedIn](https://www.linkedin.com/in/harshinijayakumar-215216319)
