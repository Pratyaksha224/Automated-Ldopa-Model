# Automated L-DOPA Drug Delivery System

A closed-loop L-DOPA drug delivery system designed using a
Pharmacokinetic-Pharmacodynamic (PK-PA) model and PID control for
automated drug regulation and reference tracking.

## Project Overview

The project focuses on developing a feedback-controlled drug delivery
system capable of regulating L-DOPA concentration according to a desired
reference value.

The system combines PK-PA modeling, PID control, and analog circuit
simulation to develop and evaluate the complete closed-loop control
architecture.

## Key Features

- PK-PA pharmacokinetic model
- Closed-loop PID control
- Reference/setpoint tracking
- PSpice-based circuit simulation
- AD844 CFOA implementation
- Filters and signal-conditioning circuits
- Sallen-Key delay circuit
- Integrator and differentiator circuits
- Transient-response analysis

## PID Controller

The PID controller was tuned using the hit-and-trial method.

- **Kp = 0.1**
- **Ki = 0.4**
- **Kd = 0.044**

The modeled plant has a gain of **5.6436** with a transport delay of
approximately **25 minutes**.

## Simulation

The complete control architecture was implemented and simulated in
**PSpice** using AD844 CFOAs and supporting analog circuit blocks.

Transient analysis was performed to evaluate the closed-loop response
and reference/setpoint tracking performance.

## Hardware Development

The corresponding hardware architecture includes multiple op-amp blocks
for filtering, delay, integration, differentiation, and supporting
control functions.

Hardware validation, DSO-based testing, and L-DOPA sensor integration
are currently ongoing.

## Team

Developed as a **3-member team** under faculty guidance.
