# 🔋 Power Modeling and Analysis for Embedded SoC Workloads

This project provides a complete framework to **model**, **measure**, and **visualize** the power consumption of embedded SoC (CPU/MCU) systems under different workloads and operating modes. It combines analytical modeling with real-time empirical data collection using low-cost power sensors.

---

## 🎯 Objective

- Model theoretical power profiles of embedded SoC systems.
- Log real-time current, voltage, and power data during various operations.
- Visualize power usage and energy consumption over time.
- Provide insights into workload efficiency and power optimization.

---

## 📦 Project Structure

- data/ # Raw CSV logs from power sensors (INA219, etc.)
- scripts/ # Python code for logging, analysis, and visualization
- hardware_setup/ # Wiring diagrams, sensor setup, photos
- plots/ # Output plots: power vs. time, energy charts
- report/ # Final analysis/report PDFs
- README.md # Project documentation (this file)
---

---

## ⚙️ Hardware & Tools

- 📍 **Microcontroller/SoC**: ESP32 / STM32 / Raspberry Pi
- 🔌 **Power Sensor**: INA219, INA260, or shunt resistor + op-amp
- 🧰 **Tools**: Python (pandas, matplotlib), logic analyzer, multimeter

---

## 📈 Example Use Cases

- Sleep vs. Active power profiling
- Sensor polling + radio transmission energy analysis
- Comparing firmware versions for energy efficiency
- Benchmarking two different SoCs

---

## 🚀 How to Run

1. **Connect INA219 Sensor** between the SoC and power supply.
2. **Configure I2C** communication on the microcontroller.
3. **Run logging script**:
   ```bash
   cd scripts
   python power_logger.py
---
✍️ Author:

Bright — Electrical & Computer Engineering
