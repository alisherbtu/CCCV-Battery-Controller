# Day 18 – CCCV Battery Controller Using MATLAB/Simulink

## Project Overview

Designed and simulated a Constant Current–Constant Voltage (CCCV) battery charging controller using MATLAB/Simulink.

The model incorporates battery voltage and current feedback, PID-based control, switching logic, and a controlled current source to regulate the charging response.

## Objectives

- Develop a battery charging controller using feedback control.
- Implement voltage and current monitoring.
- Integrate PID control and switching logic.
- Analyse battery voltage and current responses.
- Investigate the transition towards the voltage reference.

## Model Architecture

The Simulink model includes:

- Battery model
- Voltage sensor
- Current sensor
- Controlled current source
- PID controller
- Reference voltage
- Switching logic
- Feedback control loop
- Simulation display

## Simulink Model

![CCCV Battery Controller Model](Model%20.png)

## Simulation Results

The simulation shows:

- Battery voltage increasing from approximately 3.55 V to 4.2 V.
- Current starting at approximately -3 A and gradually approaching zero.
- Switching response changing around sample 2,650.
- Voltage settling near the 4.2 V reference.

The negative current represents the measurement direction used in the model.

![CCCV Battery Controller Simulation Results](switch%20IV%20.png)

## Tools and Technologies

- MATLAB
- Simulink
- PID Control
- Battery Modelling
- CCCV Charging Strategy
- Feedback Control Systems

## Learning Outcomes

Developed practical experience in battery charging control, feedback systems, PID regulation, switching logic, and simulation-based performance analysis.

---

**Project:** Day 18 – Battery Management System Development  
**Author:** Ali Sher  
**GitHub:** [alisherbtu](https://github.com/alisherbtu)
