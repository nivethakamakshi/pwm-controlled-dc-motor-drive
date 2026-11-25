PWM-Based DC Motor Speed Controller Using a MOSFET

Project Overview

This project explores the design and simulation of a PWM-based DC motor speed controller using an N-channel MOSFET.

The objective is to understand how Pulse Width Modulation (PWM) can control the average power delivered to a DC motor and how a MOSFET can act as an electronic switching device.

The project uses LTspice to develop and analyse the circuit through progressively more complex simulation experiments.

Objectives

- Understand PWM signals and duty-cycle control.
- Study the electrical behaviour of a simplified DC motor winding model.
- Understand N-channel MOSFET switching.
- Design a low-side MOSFET switching circuit.
- Investigate the role of a flyback diode in inductive-load switching.
- Analyse voltage and current waveforms under different operating conditions.

Tools and Software

Tool		Purpose
LTspice		Circuit design and simulation
VS Code		Documentation and project organisation
Git		Version control
GitHub		Project hosting and documentation

Project Development

Experiment 1: PWM Signal Generation

Generated PWM signals in LTspice and studied the effect of changing duty cycle and switching frequency.

Experiment 2: Simplified DC Motor Electrical Model

Developed a series R-L circuit to understand the relationship between winding resistance, inductance and current response.

Experiment 3: MOSFET Switching Test

Developed a resistive-load switching circuit using a generic N-channel MOSFET model and a PWM gate signal.

Experiment 4: PWM Controlled DC Motor Driver

- PWM-controlled inductive-load switching.
- Flyback diode integration.
- Duty-cycle comparison.
- Current ripple and voltage waveform analysis.


Current Scope and Limitations

The initial experiments are simulation-based.

The simplified R-L motor model does not independently represent mechanical rotation, load torque, inertia or speed-dependent back EMF.

The MOSFET switching experiment uses a simplified educational model and a resistive load. Its results should not be treated as a validated prediction of a physical motor controller.

No physical hardware implementation is claimed at this stage.

Future Improvements

- Incorporate a more realistic motor model.
- Evaluate a suitable real-world MOSFET using its datasheet model.
- Study switching losses and current ripple.
- Build and test a physical prototype.
- Compare simulation results with experimental measurements.

Learning Outcomes

This project is intended to develop practical understanding of power electronics, switching devices, PWM control and circuit simulation.
