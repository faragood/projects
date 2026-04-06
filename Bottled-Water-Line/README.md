# Automated Production Line & Robotic Palletizing

## Overview
This repository showcases the automated control logic and robotic integration for a continuous bottled water production line. The project demonstrates the seamless synchronization between a central Programmable Logic Controller (PLC) and a 6-axis industrial manipulator to execute high-speed, precise pick-and-place palletizing operations.

## Hardware & Technologies Used
* **PLC:** Schneider Electric Modicon M241 
* **Software Environment:** Schneider EcoStruxure Machine Expert
* **Programming Languages:** IEC 61131-3 Standard (Function Block Diagram - FBD, Ladder Diagram - LD)
* **Robotics:** Yaskawa Motoman MH50-35 (6-axis industrial manipulator)
* **Robot Controller:** Yaskawa DX200

## Key Features & Engineering Highlights

### 1. Robust Control Logic (FBD/LD)
* Developed comprehensive control algorithms using FBD and LD to manage the continuous flow of the bottled water production line.
* Engineered dual operating modes (Automatic and Manual) to facilitate both standard continuous production and safe maintenance/testing operations.
* Implemented strict safety interlocks to prevent equipment collisions and ensure operator safety during active production cycles.

### 2. PLC-Robot Integration
* Established reliable communication between the Schneider Modicon M241 PLC and the Yaskawa DX200 robot controller.
* Mapped digital I/O signals to trigger specific robotic palletizing trajectories based on conveyor sensor feedback and real-time product tracking.

### 3. Precision and Reliability
* Programmed the robotic manipulator's movements to achieve a high-precision placement repeatability of ±0.07 mm.
* Optimized the line logic to eliminate bottlenecks, ensuring high throughput and continuous operational reliability for the palletizing station.
