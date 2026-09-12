# Sherifred Singh
### Embedded Firmware Engineer | Industrial Automation & Control Systems
**Coimbatore, India** • [LinkedIn](https://www.linkedin.com/in/sherifredsing/) • [Email](mailto:ssherifred@gmail.com) • [Portfolio](https://sherifred123.github.io)

---

## ⚡ Summary

Embedded Firmware Developer with **6.5+ years in industrial automation** (4.5+ years dedicated to firmware engineering, preceded by 2 years in hardware testing and control system bring-up). 

Focused on register-level **Embedded C**, modular peripheral drivers, state machines, and FreeRTOS across **PIC18** and **STM32 (ARM Cortex-M)** platforms. I prioritize writing clean, predictable firmware with clear hardware abstraction, MISRA-C awareness, and robust fault handling.

---

## 🛠 Technical Skills

<p align="left">
  <!-- Core Languages & OS -->
  <img src="https://img.shields.io/badge/C%20%2F%20Embedded%20C-A8B9CC?style=for-the-badge&logo=c&logoColor=black"/>
  <img src="https://img.shields.io/badge/FreeRTOS-7F00FF?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <br>
  <!-- Silicon Platforms -->
  <img src="https://img.shields.io/badge/PIC%2016%2F18-Microchip-000000?style=for-the-badge&logo=microchip&logoColor=white"/>
  <img src="https://img.shields.io/badge/STM32%20ARM-STMicroelectronics-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white"/>
  <img src="https://img.shields.io/badge/ESP32-Espressif-E7352C?style=for-the-badge&logo=espressif&logoColor=white"/>
  <br>
  <!-- Dedicated IDEs & Build Tools -->
  <img src="https://img.shields.io/badge/MPLAB%20X-FF7A00?style=for-the-badge&logo=microchip&logoColor=white"/>
  <img src="https://img.shields.io/badge/STM32CubeIDE-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white"/>
  <img src="https://img.shields.io/badge/Keil%20µVision-00599C?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white"/>
</p>

- **Languages & Guidelines:** C, Embedded C, MISRA-C Guidelines
- **Firmware Design:** Bare-Metal Drivers, State Machines, Non-Blocking Timers, ISR Architecture
- **RTOS:** FreeRTOS (Tasks, Queues, Semaphores, Mutexes)
- **Microcontrollers:** Microchip PIC16 / PIC18, STM32 ARM Cortex-M (STM32F1), ESP32 (Basic)
- **Protocols & Busses:** UART, SPI, I2C, 1-Wire, RS-485 / Modbus RTU, CAN Bus (Basics), BLE
- **Development Tools:** MPLAB X, STM32CubeIDE, Keil µVision, Make / CMake, Unity Unit Test, Git
- **Hardware & Lab Testing:** Digital Storage Oscilloscope (DSO), Logic Analyzer, Multimeter, Schematic Review (KiCad), SMD & THT Soldering

---

## 💡 Areas of Interest

- Embedded Linux & Build Systems
- Modular Driver Architecture
- Industrial Automation & Protocol Gateways
- Real-Time Embedded Systems (RTOS)

---

## 📂 Core Firmware Modules & Driver Architecture (Open Source)

* ⭐ **[embedded-c-ring-buffer](https://github.com/Sherifred123/embedded-c-ring-buffer)** — Lock-free, thread-safe FIFO circular ring buffer in C99 for UART/SPI ISR-to-main communication.
* ⭐ **[embedded-fsm-engine](https://github.com/Sherifred123/embedded-fsm-engine)** — Table-driven Finite State Machine (FSM) framework with an Automatic Transfer Switch (ATS) industrial model.
* ⭐ **[stm32-freertos-sensor-hub](https://github.com/Sherifred123/stm32-freertos-sensor-hub)** — Multi-tasking sensor acquisition and telemetry with FreeRTOS queues, mutexes, and watchdog supervision on STM32.
* ⭐ **[industrial-sensor-hal](https://github.com/Sherifred123/industrial-sensor-hal)** — Decoupled sensor driver library for MAX6675 (SPI), DS18B20 (1-Wire with CRC8), and NTC ADC LUT interpolation.
* ⭐ **[modbus-rtu-slave-c](https://github.com/Sherifred123/modbus-rtu-slave-c)** — Lightweight Modbus-RTU slave protocol stack with fast table CRC-16 for RS-485 industrial networks.

---

## 🏭 Commercial Projects

### 🔹 Automatic Transfer Switch (ATS) Controller
**Target:** Microchip PIC18 • **Status:** Commercial Product *(Source Code Confidential)*  

*Industrial power automation controller for automated, fail-safe switching between mains grid and backup generator.*

* **Role:** Firmware Design, Driver Development & Lab Validation.

* Implemented multi-state generator & mains transfer logic with strict *break-before-make* relay interlocking to prevent cross-connection.
* Configured calibrated ADC sampling for rapid undervoltage, overvoltage, and phase-imbalance detection.
* Automated generator engine sequencing: warm-up/cool-down timing, crank/recrank cycles, and persistent fault and runtime event logging to internal EEPROM.

---

### 🔹 16-Loom Textile Production Monitor
**Target:** PIC18 / STM32 • **Status:** Commercial Product *(Source Code Confidential)*  

*Edge monitoring and logging system deployed across industrial weaving facilities.*

* **Role:** Firmware Implementation, GLCD HMI Interface & EEPROM Storage.

* Collected and aggregated real-time, shift-wise production metrics from up to 16 looms simultaneously.
* Built a power-fail-safe state snapshotting mechanism to EEPROM with RTC (DS3231) timestamping to prevent data loss during power cuts.
* Developed an interactive Graphical LCD (GLCD) menu for operator configuration, calibration, and shift reporting.

---

### 🔹 Multi-Stage Industrial Temperature Controller
**Target:** PIC18F46K22 • **Status:** Commercial Product *(Source Code Confidential)*  

*Precision cooling and compressor management controller for commercial refrigeration units.*

* **Role:** Sensor Driver Integration & Control Logic.

* Interfaced multiple sensor types: analog NTC (calibrated ADC lookup-table (LUT) linearisation), 1-Wire (DS18B20), and SPI (MAX6675 thermocouple interface).
* Implemented staged multi-compressor control with configurable differential hysteresis, anti-short-cycle delay timers, and alarm trip matrices.

---

<div align="center">
  <table border="0">
    <tr>
      <td align="center" valign="middle">
        <a href="https://github.com/Sherifred123">
          <img src="https://streak-stats.demolab.com?user=Sherifred123&theme=tokyonight&hide_border=true&date_format=j%20M%5B%20Y%5D" height="145" alt="GitHub Streak" />
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://github.com/Sherifred123">
          <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Sherifred123&theme=tokyonight" height="145" alt="GitHub Profile Details" />
        </a>
      </td>
    </tr>
  </table>
</div>
