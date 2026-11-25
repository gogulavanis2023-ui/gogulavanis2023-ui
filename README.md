# Hi, I'm Gogulavani S 👋

**Final-year B.Tech Electronics and Communication Engineering student at VIT Vellore (graduating 2027, CGPA 8.05)**

I like taking a digital design all the way from a block diagram to a working board: RTL, simulation against a reference model, timing closure, and then debugging what only shows up on real hardware. My work sits where **FPGA/RTL design, embedded systems and automotive electronics** meet.

## 🎯 What I'm looking for
I'm looking for **full-time roles (2027)** or **internships with a path to a full-time offer** in:
- **FPGA and RTL design**, and **design verification**
- **Embedded firmware** (microcontrollers, communication buses, sensors)
- **Automotive electronics** (in-vehicle networks, ECU security)
- **Semiconductor and hardware validation**

📍 Preferred locations: **Chennai** and **Bengaluru**

## 🔬 What I've built

| Project | What it shows |
|---|---|
| [**Parallel GPS C/A Code Acquisition Engine**](https://github.com/gogulavanis2023-ui/fpga-gps-ca-code-acquisition) (research internship, IIT Madras) | 32 runtime-selectable parallel correlators on an Artix-7; LFSR PRN generation; timing closed with 5.85 ns slack; on-board bring-up and debugging |
| [**Runtime-Reconfigurable Parallel FIR Filter**](https://github.com/gogulavanis2023-ui/fpga-reconfigurable-fir-filter) | 48-tap fixed-point DSP datapath; bit-exact against a Python golden model; DSP48 mapping; per-mode power analysis showing ~7× lower energy per sample at higher parallelism |
| [**CAN-Bus ECU Voltage Fingerprinting IDS**](https://github.com/gogulavanis2023-ui/can-ecu-voltage-fingerprinting-ids) | Automotive security: CAN bench (Arduino + MCP2515), STM32 guardian node, digital-twin simulation with open-set SVM and CUSUM attack detection |
| [**Asynchronous FIFO with Gray-Code CDC**](https://github.com/gogulavanis2023-ui/async-fifo-cdc-verilog) | Clock-domain crossing done properly: Gray-code pointers, synchronisers, SDC constraints, scoreboard testbench |

➡️ See the full index in [**ece-engineering-portfolio**](https://github.com/gogulavanis2023-ui/ece-engineering-portfolio).

## 💼 Experience
- **Research Intern, IIT Madras** (May–Jul 2026): GPS acquisition hardware on FPGA
- **Embedded Systems Intern, C Systems Pvt Ltd, Chennai** (May–Jul 2025): PIC-based industrial temperature monitoring firmware
- **IoT with ESP32 training, COGTIS Technologies** (Mar 2024)

## 🛠️ Tools and skills
**HDL and FPGA:** Verilog · Xilinx Vivado (synthesis, implementation, timing, power) · Intel Quartus Prime · ModelSim · Artix-7 / Basys 3 · Cyclone IV / DE2-115
**Embedded:** Embedded C · Arduino · ESP32 · STM32 · PIC · SPI · UART · CAN (MCP2515/TJA1050) · Bluetooth
**Software and analysis:** Python (NumPy, SciPy, scikit-learn) · MATLAB · LaTeX

## 🌱 What I'm working towards
- Building the **analog front end for the CAN fingerprinting guardian**, so the detection runs on real measured waveforms instead of simulated ones
- Learning **SystemVerilog and UVM-style verification** (assertions, constrained-random stimulus, coverage)
- Moving from Arduino-style APIs to **bare-metal STM32 drivers** (registers, interrupts, DMA)

## 📫 Get in touch
Open an issue on any repo or message me on GitHub. I'm happy to talk about FPGA, embedded or automotive hardware.
