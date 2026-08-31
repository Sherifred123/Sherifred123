# Sherifred Singh
### Embedded Firmware Engineer | Industrial Automation & Control Systems
**Coimbatore, India** • [LinkedIn](https://www.linkedin.com/in/sherifredsing/) • [Email](mailto:ssherifred@gmail.com)

---

## ⚡ Summary

Embedded Firmware Developer with **6.5+ years in industrial automation** (4.5+ years specialized in core firmware development, preceded by 2 years in hardware testing and control system bring-up). 

Focused on register-level **Embedded C**, modular peripheral drivers, state machines, and FreeRTOS across **PIC18** and **STM32 (ARM Cortex-M)** platforms. I prioritize writing clean, predictable firmware with clear hardware abstraction and robust fault handling.

---

## 🛠 Technical Skills

- **Languages:** C, Embedded C
- **Firmware Design:** Bare-Metal Drivers, State Machines, Non-Blocking Timers, ISR Architecture
- **RTOS:** FreeRTOS (Tasks, Queues, Semaphores, Mutexes)
- **Microcontrollers:** Microchip PIC16 / PIC18, STM32 ARM Cortex-M (STM32F1), ESP32 
- **Protocols & Busses:** UART, SPI, I2C, 1-Wire, RS-485 / Modbus RTU, BLE
- **Development Tools:** MPLAB X, STM32CubeIDE, Keil µVision, Git
- **Hardware & Lab Testing:** Digital Storage Oscilloscope (DSO), Logic Analyzer, Multimeter, SMD & THT Soldering

---

## 💡 Areas of Interest

- Embedded Linux & Build Systems
- Modular Driver Architecture
- Industrial Automation & Protocol Gateways
- Real-Time Embedded Systems (RTOS)

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
