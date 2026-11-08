# iDrink — Smart IoT Water Quality Monitoring System

> Real-time embedded water quality surveillance system with multi-sensor acquisition and IoT connectivity.

---

## Overview

**iDrink** is a smart water filtration and monitoring system built around an IoT-connected embedded platform. It continuously measures key water quality parameters and provides real-time data visualization, triggering alerts when values exceed safe thresholds.


---

## Features

- **Real-time multi-parameter monitoring** — pH, turbidity, and TDS (Total Dissolved Solids)
- **Embedded sensor fusion** — low-latency data acquisition pipeline
- **IoT connectivity** — MQTT-based data streaming to a cloud dashboard
- **Alert system** — threshold-triggered notifications for unsafe water quality
- **Low-power design** — optimized for continuous operation

---

## Hardware Architecture

```
iDrink System
├── Microcontroller: ESP32
├── Sensors
│   ├── pH Sensor          → acidity level (0–14)
│   ├── Turbidity Sensor   → water clarity (NTU)
│   └── TDS Sensor         → dissolved solids (ppm)
├── Communication: MQTT over Wi-Fi
└── Visualization: IoT Dashboard
```

---

## Tech Stack

| Component | Technology |
|-----------|-----------|
| Microcontroller | ESP32 |
| Protocol | MQTT |
| Sensors | pH, Turbidity, TDS |
| Language | C (Arduino framework) |
| Dashboard | IoT cloud platform |

---

## System Flow

```
Sensor Reading → ADC Conversion → Signal Processing → MQTT Publish → Dashboard Display
                                                    ↓
                                             Threshold Check → Alert if unsafe
```

---

## Documentation

📄 **[Full Project Report](iDrink%20%20rapport.pdf)**  
📊 **[Project Presentation](iDrink%20presentation.pdf)**  

---

## Results

- Achieved accurate real-time measurement of all three water parameters
- Successfully integrated MQTT pipeline with sub-second latency
- Deployed and tested on physical prototype

---

## Academic Context

Developed at **ENICarthage** — Mechatronics Engineering Program  
Academic Year 2024–2025
