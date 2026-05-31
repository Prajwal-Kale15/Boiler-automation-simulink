# Multi-Variable Boiler Automation using MATLAB/Simulink

## Project Overview

This project simulates an industrial boiler automation system using MATLAB/Simulink.

The system controls:

- Boiler Water Level
- Boiler Temperature

using PID-based closed-loop control.

---

## Features

- PID Controller
- Water Level Control
- Temperature Control
- Coupled Process Interaction
- Disturbance Rejection
- Safety Alarm System
- Real-Time Monitoring Dashboard

---

## Software Used

- MATLAB
- Simulink

---

## Project Structure

Water Level Loop:
Setpoint → PID → Boiler Model → Output → Feedback

Temperature Loop:
Setpoint → PID → Boiler Model → Output → Feedback

Coupling:
Water Level Output → Gain → Temperature Loop

---

## Screenshots

### Complete Model

![Model](screenshots/full_model.png)

### Water Level Response

![Water](screenshots/water_level_scope.png)

### Temperature Response

![Temp](screenshots/temperature_scope.png)

### Dashboard

![Dashboard](screenshots/dashboard.png)

---

## Author

Prajwal Kale

B.Tech Instrumentation & Control Engineering

VIT Pune