# Hardware

## 📌 Overview

This folder contains the main hardware components used in the **Team Falcons E-Kart**.

The vehicle uses a **5 kW, 60 V PMSM electric powertrain** with a lithium-ion battery pack, controller, chain drive, braking system, steering system, and safety components.

---

## ⚡ Main Hardware Components

### 1. Electric Motor

- Type: Permanent Magnet Synchronous Motor (PMSM)
- Model: DATAI 60-5000-150
- Rated Power: 5 kW
- Maximum Allowed Power: 6 kW
- Voltage: 60 V DC
- Phase: 6-Phase
- Maximum Design Speed: 3800 RPM
- Peak Torque: 58 Nm
- Continuous Torque: 16 Nm

---

### 2. Motor Controller

- Type: PMSM Controller
- Manufacturer: DATAI
- Peak Discharge: 10 kW
- Continuous Discharge: 5–6 kW

The controller manages the electrical power supplied to the PMSM motor.

---

### 3. Battery Pack

- Type: Lithium-ion
- Chemistry: NMC
- Nominal Voltage: 60 V
- Fully Charged Voltage: 67.2 V
- Capacity: 90 Ah
- Configuration: Approximately 16S × 30P
- Individual Cell Voltage: 3.7 V
- Cell Voltage Range: 3.0–4.2 V
- Peak Discharge: Approximately 9 kW
- Continuous Discharge: Approximately 5 kW
- Cooling: Passive air cooling
- Battery Management System: BMS

---

### 4. DC-DC Converter

The DC-DC converter supplies the low-voltage electrical system from the high-voltage battery system.

- Input: 48–72 V
- Output: 12 V
- Current: 15 A

---

## 🔩 Power Transmission

The motor power is transferred to the drive shaft through a chain-drive system.

| Component | Specification |
|---|---|
| Motor Sprocket | 12 Teeth |
| Final Sprocket | 48 Teeth |
| Final Drive Ratio | 4:1 |
| Drive Shaft | 25 mm |
| Keyway | 8 × 7 mm Parallel Key |
| Drive System | Chain Drive |

---

## 🛞 Wheels and Tyres

| Position | Tyre Size |
|---|---|
| Front | 10 × 4.7 × 5 in |
| Rear | 11 × 7.1 × 5 in |

---

## 🛑 Braking System

The E-Kart uses a rear disc braking system.

- Brake Disc Diameter: 220 mm
- Disc Thickness: 4.0 mm
- Brake Pedal Ratio: 4–5:1
- Approximate Human Pedal Force: 300–400 N
- Tyre-Road Friction Coefficient: Approximately 0.7

---

## 🏗️ Chassis

- Material: AISI 4130
- Outer Diameter: 25.4 mm
- Tube Thickness: 1.6 mm
- Density: 7850 kg/m³
- Young's Modulus: 205 GPa
- Yield Strength: 435 MPa
- Ultimate Tensile Strength: 560 MPa
- Poisson's Ratio: 0.29

---

## 🎛️ Steering System

- Mechanical Linkage Ratio: 10:1
- Ackermann Percentage: 37.5%
- Turning Radius: 2.7 m
- Lock-to-Lock Steering: -230° to +230°

---

## 🔌 Electrical and Safety Components

The electrical system includes:

- 150 A Automotive Blade Fuse
- 150 A DC MCB
- Accumulator Isolation Relay (AIR)
- High-voltage DC contactor
- Anderson SB 175 A connector
- Ignition key switch
- Driver-accessible kill switch
- Tractive System Disconnect
- Auxiliary 12 V battery
- 12 V digital LCD
- TSAL red LED
- RTDS buzzer
- Battery Management System (BMS)

---

## ⚡ HLV and GLV Systems

### HLV – High Voltage System

Used for propulsion and charging.

Main components:

- Battery pack
- Motor
- Inverter/controller
- High-power wiring

### GLV – Low Voltage System

Used for control and auxiliary functions.

Main components:

- ECU/control electronics
- Sensors
- Display
- Relays
- Auxiliary 12 V system

The HLV and GLV systems are electrically separated for safety.

---

## 📊 Approximate Weight Distribution

| Component | Percentage |
|---|---:|
| Chassis / Frame | 30% |
| Battery Pack | 25% |
| Motor / Controller | 15% |
| Wheels / Tyres | 10% |
| Steering | 5% |
| Electronics / Safety | 10% |
| Brakes | 5% |

---

## 📷 Component Images

Recommended images for this folder:

```text
component-images/
├── motor.jpg
├── motor-controller.jpg
├── battery-pack.jpg
├── bms.jpg
├── dc-dc-converter.jpg
├── sprocket.jpg
├── drive-shaft.jpg
├── brake-disc.jpg
├── steering-system.jpg
├── chassis.jpg
├── wheels-tyres.jpg
└── electrical-safety-components.jpg
