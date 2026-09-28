# Ignition Juice Bottling Plant SCADA

An industrial automation simulation of a juice bottling plant developed using **Inductive Automation Ignition SCADA with the Perspective Module**.

The project demonstrates real-time process monitoring, supervisory control, process visualization, safety interlocks, alarm management, equipment status monitoring, and production-oriented data visualization.

---

## Project Overview

The Juice Bottling Plant SCADA project is a software-based industrial automation simulation designed to demonstrate how a manufacturing process can be monitored and controlled through a modern SCADA system.

The system uses **Ignition Perspective** to provide a browser-based operator interface for monitoring process conditions, equipment states, safety status, alarms, and production information.

The project focuses on developing an operator-oriented SCADA interface rather than physical industrial production deployment.

---

## Key Features

- Real-time process visualization
- Ignition Perspective HMI development
- Industrial SCADA architecture
- Equipment status monitoring
- Start/Stop control
- Safety interlocks
- Emergency-stop indication
- Alarm monitoring
- Fault indication
- Process status visualization
- Production monitoring
- Tank/level monitoring
- Conveyor/process monitoring
- Historical data and trend concepts
- Operator-oriented dashboard design
- PLC/SCADA communication concepts
- Industrial automation workflow

---

## Technology Stack

| Technology | Purpose |
|---|---|
| Ignition SCADA | Supervisory control and monitoring |
| Ignition Perspective | Browser-based HMI / visualization |
| Ignition Gateway | SCADA runtime and communication layer |
| PLC / PLC Simulation | Control logic representation |
| OPC UA | Industrial communication |
| SQL / Database | Historical and production data concepts |
| Industrial Automation | Process control architecture |

---

# System Architecture

The project follows a layered industrial automation architecture:

```text
+-----------------------------+
|       Operator / User       |
+-------------+---------------+
              |
              v
+-----------------------------+
|    Ignition Perspective     |
|       HMI / Dashboard       |
+-------------+---------------+
              |
              v
+-----------------------------+
|       Ignition Gateway      |
|   Tags / Alarms / Services  |
+-------------+---------------+
              |
              v
+-----------------------------+
|          OPC UA             |
|  Industrial Communication   |
+-------------+---------------+
              |
              v
+-----------------------------+
|       PLC / Simulation      |
|       Control Logic         |
+-------------+---------------+
              |
              v
+-----------------------------+
|     Simulated Process       |
| Juice Bottling Operations   |
+-----------------------------+
