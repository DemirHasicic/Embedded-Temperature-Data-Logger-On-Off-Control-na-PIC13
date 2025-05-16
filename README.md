# Embedded Temperature Monitoring & Bang–Bang Control System

An embedded solution for temperature monitoring and regulation, built around a PIC13 microcontroller. The system periodically samples two LM35 temperature sensors, logs readings in EEPROM, and displays current values on a 4-bit LCD. When the temperature crosses predefined upper or lower thresholds, it drives a heater or fan using bang–bang (on/off) control. The project includes precise timer configuration, a custom LCD driver, Proteus-based validation, and a custom PCB layout in KiCad.

---

## Features

- **Dual-sensor sampling** of two LM35 temperature probes every 10 s  
- **EEPROM logging** to preserve readings across power cycles  
- **4-bit LCD driver** for real-time display of internal/external temperatures  
- **Bang–bang control** for heating and cooling based on upper/lower thresholds  
- **Proteus simulation** for logic validation and threshold tuning  
- **Custom PCB layout** integrating MCU, sensors, display, and power circuitry  

---

## Hardware Requirements

- PIC13Fxxxx MCU (e.g. PIC16F1939)  
- Two LM35 temperature sensors  
- 4-bit character LCD (HD44780-compatible)  
- Heater (e.g. resistive element) and cooling fan  
- EEPROM (built into PIC or external)  
- Power supply (5 V)  
- Optional: PICkit3 or other ICD programmer  

---

## Software Requirements

- **MPLAB X IDE**  
- **XC8 C Compiler** (for PIC13 family)  
- **Proteus** (for schematic simulation)  
- **Git** (version control)  

---
