# Embodied Cognition in Robotics (ROS1)

Implementation of neural field dynamics and perceptual binding for real-robot navigation.

Official implementation accompanying the paper:

**Embodied Cognition in Robotics via Neural Field Dynamics and Perceptual Binding**

---

## Overview

This repository contains a ROS1 implementation of an embodied cognition-inspired navigation framework based on:

- Neural field dynamics
- Perceptual binding
- Continuous sensorimotor coupling
- Field-based motor control

Test platform:
- TurtleBot3 Burger
- RPLiDAR A1
- ROS1 Noetic

---

## Repository Structure

- `config/` → neural field parameters
- `launch/` → ROS launch files
- `src/` → core nodes (perception, binding, memory, motor)
- `experiments/` → validation protocol

---

## Running (example)

```bash
roslaunch embodied_navigation.launch
