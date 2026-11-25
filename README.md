
# Inverted Pendulum Simulation and PID Tuning

A simulation-based project developed using CoppeliaSim to study and tune a PID controller for an inverted pendulum system. The project focuses on understanding system dynamics, achieving pendulum stabilization, and experimenting with PID parameters in a virtual environment.

## Project Overview

The inverted pendulum is an inherently unstable system that requires continuous control to maintain its upright position.

This project involves simulating an inverted pendulum in CoppeliaSim and experimenting with PID controller parameters to achieve stable balancing. Different PID gains are adjusted and tested to observe their effects on system response, stability, oscillations, and settling behaviour.

## Project Objectives

- Simulate an inverted pendulum system in CoppeliaSim.
- Understand the dynamics of an inherently unstable system.
- Implement and experiment with PID control.
- Tune Proportional, Integral, and Derivative gains.
- Observe the effects of different PID parameters on system stability.
- Study transient response, oscillations, and settling time.

## Simulation Environment

- Simulation Software: CoppeliaSim
- System: Inverted Pendulum
- Control Technique: PID (Proportional–Integral–Derivative)
- Application: Feedback Control and System Stabilization

## PID Controller

The PID controller continuously calculates the control error and generates corrective action to stabilize the inverted pendulum.

The control output is calculated using:

```text
u(t) = Kp * e(t) + Ki * integral(e(t)) + Kd * de(t)/dt
```

Where:

- Kp: Proportional Gain
- Ki: Integral Gain
- Kd: Derivative Gain
- e(t): Difference between the desired and actual pendulum position
- u(t): Control output

## Working Principle

1. The inverted pendulum is initialized in the simulation environment.
2. The controller monitors the pendulum's deviation from its desired upright position.
3. The PID controller calculates the corrective control signal.
4. The control signal is applied to the system to counteract the pendulum's movement.
5. PID parameters are adjusted to improve the balancing response.
6. The simulation is repeated to evaluate the controller's performance.

## Key Concepts Explored

- Inverted Pendulum Dynamics
- PID Controller Design
- PID Gain Tuning
- Feedback Control Systems
- System Stability
- Transient Response
- Oscillation and Settling Behaviour
- Simulation-Based Control Engineering

## Project Demonstration

Video: https://youtu.be/EzlwsMPsZzk

## Project Details

- Project Type: Personal Project
- Simulation Platform: CoppeliaSim
- Control Algorithm: PID
- Domain: Robotics, Control Systems, and Simulation
- Development: Independently developed and tested.

## Developer

Suprit Nandlaskar

GitHub: https://github.com/supritN

## License

This project is open-source and available for learning and educational purposes.
```
