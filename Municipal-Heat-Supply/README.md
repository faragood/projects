# P&ID Design & Control Systems Architecture

## Overview
This repository contains functional automation schemes (P&ID), hardware architectures, and tag databases for two major industrial systems: a Municipal Heat Supply Complex and a High Pressure Desuperheater. The projects focus on process instrumentation mapping, network data routing, and precise PLC hardware allocation.

## Hardware & Technologies Used
* **PLC Platform:** Schneider Electric Modicon M340 (BMX P34 2020)
* **Instrumentation:** Endress+Hauser PT100 RTDs, Cerabar pressure transmitters, Dynapar encoders
* **Industrial Networks:** Modbus RTU (RS-485)
* **External Equipment:** SPT 941.20 heat-quantity calculator, Variable Frequency Converters
* **Design Tools:** AutoCAD

## Key Features & Engineering Highlights

### 1. Municipal Heat Supply Complex
* Designed detailed functional automation schemes (P&ID) for a municipal pump station, incorporating 2 KAP pump groups, 36 motorized gate valves, and multiple pressure/temperature transmitters.
* Built a structured PLC tag database mapping AI/DI/DO signals for seamless integration of field instrumentation and variable frequency converters.
* Configured multi-layer data routing and telemetry via RS-485 Modbus RTU, successfully integrating the Schneider Electric PLC with an SPT 941.20 heat-quantity calculator.

### 2. High Pressure Desuperheater
* Designed complete functional automation schemes (P&ID) for a High Pressure Desuperheater, mapping temperature transmitters, control valves, and indicator controllers.
* Developed the full PLC hardware architecture based on the Schneider Modicon M340, detailing analog/discrete I/O module allocation and network interfaces.
