# E-Kart System Overview

## 1. Project Introduction

The **Team Falcons E-Kart** is a battery-powered electric racing kart developed at **Knowledge Institute of Technology**.

The project focuses on the design, fabrication, assembly, electrical integration, testing, and optimization of an electric go-kart.

The vehicle uses a **5 kW Permanent Magnet Synchronous Motor (PMSM)** supplied from a **60 V lithium-ion battery system**. The design considers chassis strength, weight distribution, steering geometry, braking performance, electrical safety, driver ergonomics, and power transmission.

### Project Identification

| Parameter | Specification |
|---|---|
| Team | Team Falcons |
| Team VIN | 2606EV401 |
| Institution | Knowledge Institute of Technology |
| Motor Category | 5 kW |
| Primary Fabrication Responsibility | Aravinth R – Fabrication Head |

---

# 2. Overall Vehicle Architecture

The E-Kart can be divided into the following major systems:

```text
                         E-KART SYSTEM
                              │
       ┌──────────────────────┼──────────────────────┐
       │                      │                      │
   Mechanical             Electrical             Safety
     System                 System                System
       │                      │                      │
 ┌─────┼─────┐        ┌──────┼──────┐        ┌─────┼─────┐
 │     │     │        │      │      │        │     │     │
Chassis Steering     Battery Motor Controller BMS Kill  TSD
       │   Braking       │      │      │        │    Switch
       │     │           └──────┴──────┘        │
       │ Wheels & Tyres                           │
       │                                          │
       └────────────── Vehicle Integration ──────┘
