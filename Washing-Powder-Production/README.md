# Automated Control System for Washing Powder Production Line

## Overview
This project presents a comprehensive electrical and control system design for a fully automated continuous washing powder production line. The architecture covers power distribution, sensor/actuator integration, and relay-contactor motor control logic for six main production stages: Mixer, Disperser, Granulator, Fluid Bed Dryer, Filtration System, and Packaging Machine.

The central automation unit orchestrating the process is the **Siemens SIMATIC S7-1500 Programmable Logic Controller (PLC)**.

## 🛠️ Hardware & Technologies Used
* **PLC:** Siemens SIMATIC S7-1500 (AI, DI, DQ, and HSC modules).
* **Primary Motor:** 18.5 kW Siemens SIMOTICS SD 1LE1503-1EB2 Severe Duty induction motor (Cast Iron, IE3).
* **Sensors & Instrumentation:** * Pressure & Level:* Siemens SITRANS P DS III
  * *Temperature:* Siemens SITRANS TS500 with TH420 transmitter
  * *Flow:* Siemens SITRANS F M MAG 5100 W
  * *Speed/RPM:* Siemens SITRANS WS300 (HSC integration)
  * *Humidity & Vibration:* Siemens QFM2171, IFM VTV122
* **Low-Voltage Protection:** Schneider Electric Compact NSX160F, Acti9 iC60H (Type D), EKF KME Contactors, EKF RT-820M Thermal Relays.
* **Engineering Tools:** AutoCAD, NI Multisim.

##  Project Architecture & Stages

### Stage 1: Power Distribution & Protection
* Developed the main electrical wiring schematics ensuring robust defense against high inrush currents.
* Conducted cross-section area calculations for copper wiring based on maximum load currents and specific device efficiency/power factors.
* Selected Type D Miniature Circuit Breakers (MCBs) specifically to accommodate high initial motor surges without nuisance tripping.

### Stage 2: Sensor Integration & I/O Mapping
* Mapped all field sensors to the Siemens S7-1500 I/O modules.
* Configured analog inputs (4-20 mA) for continuous tracking of temperature, pressure, and fluid dosing.
* Integrated High-Speed Counter (HSC) inputs for contactless drum rotation speed monitoring (SITRANS WS300) to ensure granule quality.

### Stage 3: Motor Analysis & Star-Delta Control
* Performed a detailed technical comparison between Siemens 1LE1503 (Cast Iron) and Brook Crompton BA4M025-4 (Aluminum) motors. 
* Selected the Siemens motor for its superior vibration damping, higher starting torque (300 Nm), and thermal service factor (SF 1.15) suitable for heavy-duty mixing.
* Designed a **Star-Delta relay-contactor starting circuit** to safely limit the 720% (252 A) inrush current, preventing voltage sags in the industrial grid. Included electrical interlocking for safety.

## Schematics & Diagrams
*(Add screenshots of your AutoCAD diagrams here by dragging and dropping them into the editor)*

* **Power Distribution Scheme:** `[Insert Screenshot of ACD_SIS1_Schem]`
* **Sensor Connection Diagram:** `[Insert Screenshot of ACD_SIS2_Model]`
* **Star-Delta Motor Control Circuit:** `[Insert Screenshot of ACD_SIS3_Schema]`

##  Repository Contents
* `ACD_SIS1_Report.pdf` & `ACD_SIS1_Schem.pdf` - Power Distribution and calculations.
* `ACD_SIS2_Report.pdf` & `ACD_SIS2_Model.pdf` - Instrumentation and I/O mapping.
* `ACD_SIS3_Report.pdf` & `ACD_SIS3_Schema.pdf` - Motor analysis and control circuit design.
