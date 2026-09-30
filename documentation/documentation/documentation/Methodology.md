# E-Kart Development Methodology

## 1. Overview

The Team Falcons E-Kart was developed through a structured engineering process covering vehicle requirements, research, benchmarking, CAD design, component selection, structural analysis, procurement, fabrication, assembly, testing, and performance validation.

The overall methodology was:

```text
Concept & Objectives
        ↓
Literature Review / Research
        ↓
Benchmarking
        ↓
CAD Modelling
        ↓
BOM Preparation
        ↓
Component Selection
        ↓
ANSYS Analysis
        ↓
Procurement
        ↓
Fabrication / Manufacturing
        ↓
Assembly & Wiring
        ↓
Testing & Troubleshooting
        ↓
Performance Validation
        ↓
Optimization
        ↓
Final Documentation


2. Concept and Objective Definition

The first stage was to define the requirements of the electric racing kart.

The project objectives included:

Design an electric go-kart.
Develop the chassis and vehicle structure.
Select a suitable electric motor.
Select the battery and controller.
Develop the power transmission system.
Consider weight distribution.
Design steering and braking systems.
Integrate electrical and mechanical systems.
Consider driver safety.
Test and validate the completed vehicle.

The project specifically focused on electric vehicle technology, energy storage, power management, motor control, mechanical fabrication, electrical wiring, component integration, and system testing.

3. Literature Review and Research

The project schedule included a literature review and research stage.

Purpose

The research stage was used to understand:

Electric vehicle technology
Electric motor systems
Battery systems
Power management
Chassis design
Steering systems
Braking systems
Driver safety
Electric kart design

The research stage was followed by benchmarking of existing electric kart models.

4. Benchmarking

Existing electric kart models were compared during the benchmarking stage.

The project schedule allocated:

Week 2–3 for benchmarking
Comparison of existing electric kart models

Benchmarking supported the development of the vehicle layout and selection of suitable design parameters.

5. Initial Chassis Layout

After studying the vehicle requirements, the initial chassis layout was prepared using hand sketches.

The layout provided the starting point for:

Chassis geometry
Component arrangement
Driver position
Wheel placement
Steering arrangement
Powertrain packaging
6. CAD Modelling

The chassis and vehicle components were modelled using SolidWorks.

CAD Development

The CAD stage included:

Chassis modelling
Frame development
Component arrangement
Vehicle layout
Assembly development

The vehicle was represented through multiple views:

Front view
Rear view
Top view
Left-side view
Right-side view
Isometric view

The final CAD model was prepared before fabrication.

7. Chassis Material Selection

The chassis material selected was AISI 4130.

Material Properties
Property	Value
Outer Diameter	25.4 mm
Thickness	1.6 mm
Density	7850 kg/m³
Young's Modulus	205 GPa
Poisson's Ratio	0.29
Yield Strength	435 MPa
Ultimate Tensile Strength	560 MPa

The material data was incorporated into the structural analysis of the chassis.

8. Structural Analysis

The chassis was analysed using ANSYS Workbench.

The purpose was to verify:

Structural strength
Deformation behaviour
Response under the documented load cases

A load of 3000 N was documented for:

Front loading
Rear loading
Side loading
Roll-over loading
Analysis Results
Load Case	Load	Deformation	FOS
Front	3000 N	1.0008 mm	0.16
Rear	3000 N	0.897 mm	0.18
Side	3000 N	0.616 mm	0.15
Roll-over	3000 N	0.214 mm	1.2

The values are reproduced as documented in the project presentation.

9. Design Finalization

Following CAD modelling and structural analysis, the optimized design was finalized for assembly and fabrication.

The design process therefore followed:

Initial Concept
      ↓
Hand Sketch
      ↓
SolidWorks Model
      ↓
ANSYS Analysis
      ↓
Design Optimization
      ↓
Final Design
10. Bill of Materials

A Bill of Materials (BOM) was prepared during the design stage.

The BOM supported identification and procurement of the main vehicle components.

Major systems included:

Mechanical
Chassis
Steering components
Brake components
Wheels and tyres
Drive shaft
Sprockets
Chain-drive components
Electrical
PMSM motor
Motor controller
Battery pack
BMS
DC-DC converter
Fuse
DC MCB
AIR
Anderson connector
Kill switch
TSD
Digital LCD
TSAL
RTDS
11. Motor Selection

The selected motor was:

DATAI 60-5000-150 PMSM

Motor Parameters
Parameter	Value
Motor Type	PMSM
Power	5 kW
Maximum Allowed	6 kW
Voltage	60 V DC
Phase	6-Phase
Maximum Design Speed	3800 RPM
Peak Torque	58 Nm
Continuous Torque	16 Nm
Peak Power	9 kW @ 3800 RPM
Continuous Power	5 kW @ 3000 RPM

The motor was paired with a DATAI PMSM controller.

12. Battery Selection

The selected energy-storage system was a lithium-ion NMC battery pack.

Battery Parameters
Parameter	Specification
Chemistry	NMC
Nominal Voltage	60 V
Fully Charged Voltage	67.2 V
Capacity	90 Ah
Configuration	Approximately 16S × 30P
Peak Discharge	~9 kW
Continuous Discharge	~5 kW
Cooling	Passive Air Cooling
Protection	BMS

The documented charging time was 5–6 hours.

13. Powertrain Development

The selected powertrain uses a chain-drive transmission.

PMSM
 ↓
12T Motor Sprocket
 ↓
Chain
 ↓
48T Final Sprocket
 ↓
25 mm Drive Shaft
 ↓
Driven Wheels
Transmission Parameters
Parameter	Value
Motor Sprocket	12 Teeth
Final Sprocket	48 Teeth
Final Drive Ratio	4:1
Drive Shaft	25 mm
Keyway	8 × 7 mm
14. Steering System Development

The steering system was developed using mechanical linkage and Ackermann geometry.

Parameters
Parameter	Value
Steering Wheel Radius	5 inch
Linkage Ratio	10:1
Ackermann Percentage	37.5%
Turning Radius	2.7 m
Lock-to-Lock	-230° to +230°

The documented steering-angle data was evaluated at different inside steering angles.

15. Braking System Development

The vehicle uses a rear disc brake.

Brake Parameters
Disc diameter: 220 mm
Disc thickness: 4.0 mm
Pedal ratio: 4–5:1
Human pedal force: approximately 300–400 N
Pad/disc friction coefficient: approximately 0.35–0.4
Tyre-road friction coefficient: approximately 0.7

The project presentation gives the following relationships for brake-system calculations:

Master Cylinder Force
F = Pedal Ratio × Human Pedal Force

Brake Line Pressure
P = F / A

Clamping Force
F = P × A

Brake Torque
T = F × R

where the effective brake radius is approximately 0.11–0.12 m.

16. Procurement

After component selection and analysis, procurement was carried out.

The project schedule allocated:

Week 6–7 — Procurement of Materials & Components

The procurement stage provided the components required for:

Chassis fabrication
Powertrain
Battery system
Transmission
Braking
Steering
Electrical system
Safety system
17. Fabrication and Manufacturing

The documented fabrication stage was:

Week 7–9 — Fabrication / Manufacturing of Chassis & Parts

The fabrication stage followed the finalized CAD and analysed design.

The major fabrication target was the chassis and associated vehicle parts.

The presentation does not specify individual fabrication processes such as welding, cutting, drilling, or machining, so those processes are not listed here as project facts.

18. Assembly and Wiring

The documented assembly stage was:

Week 8–9 — Assembly of Components & Wiring

Mechanical and electrical systems were integrated into the completed vehicle.

Mechanical Integration
Chassis
Motor
Transmission
Drive shaft
Wheels
Steering
Brakes
Electrical Integration
Battery
Motor controller
BMS
DC-DC converter
Fuse
MCB
AIR
Connectors
Safety switches
Display
Warning systems
19. HLV and GLV Integration

The vehicle electrical architecture was divided into:

HLV

High voltage used for:

Propulsion
Charging
Motor
Inverter/controller
High-power wiring
GLV

Low voltage used for:

Control
Sensors
Display
Relays
Auxiliary functions

The presentation specifies that the HLV system requires insulation, shielding and interlocks.

20. Testing and Troubleshooting

The documented testing stage was:

Week 9–10

The project included:

Testing
Troubleshooting
Multiple iterations

Testing followed the mechanical and electrical assembly stage.

The purpose was to identify issues during system integration before final performance validation.

21. Performance Validation

Performance validation was scheduled for:

Week 10–11

The validation stage followed testing and troubleshooting.

The project schedule identifies this stage as:

Performance Validation & Optimization

The presentation does not provide detailed measured values for:

Maximum vehicle speed
Acceleration time
Driving range
Energy consumption
Lap time

Therefore, these values should not be added to the GitHub documentation unless separate test records are available.

22. Optimization

Optimization followed the testing and performance-validation stages.

The overall objective was to improve the vehicle design while considering:

Energy consumption
Vehicle stability
Chassis behaviour
Powertrain integration
Braking
Steering
Driver safety
23. Final System Integration

The final engineering workflow can be represented as:

        CHASSIS
           │
           ├──────── Steering
           │
           ├──────── Braking
           │
           └──────── Wheels
           
        POWER SYSTEM
           │
     Battery Pack
           ↓
      Controller
           ↓
       PMSM Motor
           ↓
      Chain Drive
           ↓
       Drive Shaft
           ↓
        Wheels

      SAFETY SYSTEM
           │
     ┌─────┼──────┐
     │     │      │
    BMS   AIR    TSD
     │
  Kill Switch
     │
 TSAL / RTDS
24. Complete Methodology Summary
1. Define Vehicle Requirements
            ↓
2. Research EV Technology
            ↓
3. Benchmark Existing Electric Karts
            ↓
4. Prepare Initial Chassis Layout
            ↓
5. Develop SolidWorks CAD Model
            ↓
6. Prepare Bill of Materials
            ↓
7. Select Motor, Battery & Controller
            ↓
8. Perform ANSYS Structural Analysis
            ↓
9. Optimize and Finalize Design
            ↓
10. Procure Materials & Components
            ↓
11. Fabricate Chassis & Parts
            ↓
12. Assemble Mechanical Systems
            ↓
13. Complete Electrical Wiring
            ↓
14. Test and Troubleshoot
            ↓
15. Validate Performance
            ↓
16. Optimize Vehicle
            ↓
17. Complete Documentation
25. Technical Skills Demonstrated

The project methodology provided practical exposure to:

SolidWorks CAD modelling
ANSYS Workbench
Chassis structural analysis
AISI 4130 material selection
Electric motor selection
Battery-system selection
PMSM powertrain
Chain-drive transmission
Steering geometry
Brake-system calculations
High-voltage/low-voltage architecture
Mechanical fabrication
Electrical wiring
Component integration
Testing and troubleshooting
Vehicle performance validation
