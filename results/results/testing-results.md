# Testing Results

## 📌 Overview

This document records the documented analysis and validation data of the **Team Falcons E-Kart**.

The vehicle development included chassis analysis, component integration, testing, troubleshooting, and performance validation.

---

## 🔬 Chassis Structural Analysis

The chassis was analysed using **ANSYS Workbench**.

### Applied Load

- Load: **3000 N**

### Analysis Results

| Load Case | Total Deformation |
|---|---:|
| Front | 1.0008 mm |
| Rear | 0.897 mm |
| Side | 0.616 mm |
| Roll-over | 0.214 mm |

### Factor of Safety

| Load Case | FOS |
|---|---:|
| Front | 0.16 |
| Rear | 0.18 |
| Side | 0.15 |
| Roll-over | 1.2 |

> The values above are reproduced from the Team Falcons presentation.

---

## 🏎️ Vehicle Dimensions

| Parameter | Result |
|---|---:|
| Overall Length | 1700 mm |
| Wheelbase | 1100 mm |
| Front Track | 700 mm |
| Rear Track | 720 mm |
| Ground Clearance | 50 mm |
| Overall Height | 900 mm |

---

## ⚡ Powertrain Configuration

| Parameter | Value |
|---|---:|
| Motor | PMSM |
| Motor Power | 5 kW |
| Nominal System Voltage | 60 V |
| Peak Torque | 58 Nm |
| Continuous Torque | 16 Nm |
| Maximum Design RPM | 3800 RPM |
| Battery Capacity | 90 Ah |
| Battery Chemistry | NMC |
| Final Drive Ratio | 4:1 |

---

## 🛞 Steering Results

| Parameter | Value |
|---|---:|
| Ackermann Percentage | 37.5% |
| Turning Radius | 2.7 m |
| Mechanical Linkage Ratio | 10:1 |
| Lock-to-Lock Angle | -230° to +230° |

---

## 🛑 Braking Configuration

| Parameter | Value |
|---|---:|
| Brake Position | Rear |
| Disc Diameter | 220 mm |
| Disc Thickness | 4.0 mm |
| Pedal Ratio | 4–5:1 |
| Human Pedal Force | 300–400 N |

---

## 🔧 Development Validation

The documented development sequence was:

```text
CAD Design
    ↓
ANSYS Analysis
    ↓
Component Selection
    ↓
Procurement
    ↓
Fabrication
    ↓
Assembly & Wiring
    ↓
Testing
    ↓
Troubleshooting
    ↓
Performance Validation
    ↓
Optimization
