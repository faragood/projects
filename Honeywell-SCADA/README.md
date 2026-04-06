# SCADA Point Configuration & Scripting

## Overview
This repository demonstrates the configuration, scripting, and management of a SCADA system using Honeywell Experion PKS. The project encompasses point database creation, custom VBScript development for dynamic HMI elements, comprehensive alarm management, historical data archiving, and automated reporting.

## Software & Technologies Used
* **SCADA/DCS System:** Honeywell Experion PKS
* **Configuration Tools:** Quick Builder, Experion Station
* **HMI Development:** HMIWeb Display Builder
* **Scripting Language:** VBScript

## Key Features & Engineering Highlights

### 1. Point Configuration & Alarm Management
* Configured process points (such as analog point TIC101) and established precise alarm parameters within Experion Station.
* Defined multi-level alarm limits including PV High, PV Low, PV High-High, and PV Low-Low to ensure safe operational boundaries.

### 2. Custom VBScript & Process Simulation
* Programmed custom VBScript event handlers (`OnAlarm`, `OnAcknowledge`) to dynamically alter HMI object properties and colors based on real-time alarm states.
* Engineered a mathematical Sine Wave simulation function using VBScript to generate dynamic Process Variable (PV) data for system testing and monitoring visualization.

### 3. Data Archiving & Historian
* Configured the Experion PKS Historian for long-term process data retention.
* Created dedicated history groups and assigned specific analog/digital points to track historical trends and facilitate data analysis through trend displays.

### 4. Automated System Reporting
* Developed standard system reports, including Point, Alarm, Event, and Message reports, to document operational performance.
* Configured scheduled execution of reports with automated output routing to files or printers for process management review.
