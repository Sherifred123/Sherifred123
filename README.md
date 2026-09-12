# Sherifred Singh
### Embedded Firmware Engineer | Industrial Automation & Control Systems
**Coimbatore, India** • [LinkedIn](https://www.linkedin.com/in/sherifredsing/) • [Email](mailto:ssherifred@gmail.com) • [Portfolio](https://sherifred123.github.io/PORTFOLIO/)

---

## ⚡ Summary

Embedded Firmware Developer with **6.5+ years in industrial automation** (4.5+ years specialized in core firmware development, preceded by 2 years in hardware testing and control system bring-up). 

Focused on register-level **Embedded C**, modular peripheral drivers, state machines, and FreeRTOS across **PIC18** and **STM32 (ARM Cortex-M)** platforms. I prioritize writing clean, predictable firmware with clear hardware abstraction, MISRA-C awareness, and robust fault handling.

---

## 🛠 Technical Skills

<p align="left">
  <!-- Core Languages & OS -->
  <img src="https://img.shields.io/badge/C%20%2F%20Embedded%20C-A8B9CC?style=for-the-badge&logo=c&logoColor=black"/>
  <img src="https://img.shields.io/badge/FreeRTOS-008080?style=for-the-badge&logo=c&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
</p>

<p align="left">
  <!-- Microcontrollers & Toolchains -->
  <img src="https://img.shields.io/badge/PIC16%20%2F%20PIC18%20(Microchip)-FF6600?style=for-the-badge&logo=microchip&logoColor=white"/>
  <img src="https://img.shields.io/badge/STM32%20ARM%20Cortex--M-032347?style=for-the-badge&logo=stmicroelectronics&logoColor=white"/>
  <img src="https://img.shields.io/badge/MPLAB%20X%20%2F%20XC8-EE0000?style=for-the-badge&logo=microchip&logoColor=white"/>
  <img src="https://img.shields.io/badge/STM32CubeIDE-032347?style=for-the-badge&logo=stmicroelectronics&logoColor=white"/>
</p>

<p align="left">
  <!-- Protocols & Tooling -->
  <img src="https://img.shields.io/badge/Protocols-Modbus%20RTU%20%7C%20UART%20%7C%20SPI%20%7C%20I2C%20%7C%20RS--485-2E8B57?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Git%20%26%20CI%2FCD-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Logic%20Analyzer%20%2F%20DSO-4682B4?style=for-the-badge"/>
</p>

- **Core Languages & Standards:** Embedded C (C99/C11), Python (Automated HIL testing / CLI scripting), MISRA-C awareness.
- **Architectures & MCUs:** Microchip PIC16F / PIC18F, ST STM32 (ARM Cortex-M0/M4), ESP32.
- **Real-Time Systems & Architecture:** FreeRTOS (Task synchronization, Mutexes, Semaphores, Queues), Event-Driven Super-Loops, Hierarchical State Machines (FSM).
- **Communication & Busses:** Modbus RTU, RS-485, UART (DMA / Ring Buffer driven), SPI, I2C, 1-Wire.
- **Hardware Integration & Bring-Up:** MAX6675/MAX31855 (Thermocouple), DS18B20 (1-Wire Temperature), NTC Thermistors (LUT / Steinhart-Hart), Relays, Triacs, Optocouplers, Rotary Encoders.
- **Tools & Testing:** MPLAB X IDE, XC8 Compiler, STM32CubeIDE / STM32CubeMX, Logic Analyzers (Saleae / PulseView), Digital Storage Oscilloscopes (DSO), Git, GitHub Actions.

---

## 🚀 Featured Open-Source Projects

Production-grade, modular C libraries with unit test suites and automated GitHub Actions CI/CD workflows:

| Project | Description | Platform / Key Features |
| :--- | :--- | :--- |
| 🔄 **[embedded-c-ring-buffer](https://github.com/Sherifred123/embedded-c-ring-buffer)** | SPSC Lock-Free Circular Buffer | Power-of-two bitmask indexing, atomic head/tail, zero dynamic allocation, CI tested. |
| ⚙️ **[embedded-fsm-engine](https://github.com/Sherifred123/embedded-fsm-engine)** | Event-Driven State Machine Engine | Table-driven transition matrix, automatic transfer switch (ATS) implementation, guarded actions. |
| ⚡ **[stm32-freertos-sensor-hub](https://github.com/Sherifred123/stm32-freertos-sensor-hub)** | Multi-Task Sensor Hub & Telemetry | FreeRTOS queue-based IPC, mutex-guarded UART bus, watchdog keepalive task, CMSIS-RTOS. |
| 🌡️ **[industrial-sensor-hal](https://github.com/Sherifred123/industrial-sensor-hal)** | Hardware Abstraction Layer for Sensors | Bit-banged SPI MAX6675, DS18B20 1-Wire with CRC8 verification, NTC LUT interpolator. |
| 📡 **[modbus-rtu-slave-c](https://github.com/Sherifred123/modbus-rtu-slave-c)** | Industrial Modbus RTU Slave Stack | Function codes 03, 04, 06, 16, standard CRC16 table/bitwise engine, frame validator. |

---

## 🏭 Commercial Industrial Product Experience

> *Note: Proprietary commercial firmware developed under company NDA. Architecture and technical implementations summarized below:*

- 🔒 **Rotary Oven Automation Controller:** Multi-stage baking profile sequencer, PID temperature regulation (MAX6675 thermocouple), safety interlocking, and fault diagnostic state machine.
- 🔒 **Automatic Power Factor Controller (APFC):** Real-time 3-phase grid power factor calculation, zero-crossing relay/contactor step switching algorithm, and over-current protection.
- 🔒 **Industrial Generator / Engine Control Unit (AMF/ATS):** Auto-mains failure detection, crank timing engine sequencer, engine telemetry monitoring, and Modbus RS-485 SCADA integration.

---

## 📬 Connect With Me

- **LinkedIn:** [linkedin.com/in/sherifredsing](https://www.linkedin.com/in/sherifredsing/)
- **Email:** [ssherifred@gmail.com](mailto:ssherifred@gmail.com)
- **Interactive Portfolio:** [sherifred123.github.io/PORTFOLIO](https://sherifred123.github.io/PORTFOLIO/)
