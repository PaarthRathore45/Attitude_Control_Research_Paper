# Attitude Control Research Paper

A research project exploring **attitude control** through a physical **see-saw model** and a **Python simulation**, supported by an **control algorithm** programmed in **Arduino**. This repository contains both the simulation code and the microcontroller code used to test balancing behavior in real time.

## 🧠 Project Overview

This project investigates how a control algorithm can most effectively stabilize a see-saw-like system, which serves as a simplified representation of drone attitude dynamics.  
It includes:

- A **Python simulation** modeling the physics and control of the system.
- An **Arduino program** that runs the control algorithm on real hardware, driving motors/propellers to balance the platform.

The goal is to help visualize, test, and understand control theory concepts (e.g., stability, error correction, and feedback loops).

## 📂 Repository Structure

```plaintext
AttitudeControlResearchPaper/
│
├── See_Saw_Model_Control_Algorithm.ino      # Arduino code for the physical balancing system
├── See_Saw_Model_Simulation_Code.py         # Python simulation of the see-saw control model
└── README.md                                # Project documentation
