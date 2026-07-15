# NeuralIK-FPGA

## Overview

NeuralIK-FPGA is a hardware-accelerated inverse kinematics research project that investigates the use of neural network inference on FPGA platforms for real-time robotic manipulation.

The project implements a neural inverse kinematics engine on a Xilinx Artix-7 FPGA using Verilog and compares its performance against conventional CPU-based inverse kinematics approaches, including MATLAB analytical inverse kinematics solvers and the QuIK inverse kinematics algorithm.

The primary objective is to evaluate whether FPGA-based neural inference can provide lower latency, greater determinism, and improved real-time performance for 6-DOF robotic manipulators.

## Objectives

- Design and train a neural network for 6-DOF inverse kinematics.
- Implement FPGA-based inference on a Xilinx Artix-7 platform.
- Measure inference latency and throughput.
- Compare performance against:
  - MATLAB analytical inverse kinematics
  - QuIK inverse kinematics running on a CPU
- Evaluate suitability for real-time robotic manipulation and embedded control systems.

## Hardware and Software

### Hardware
- Xilinx Artix-7 FPGA
- Embedded motor control interface
- 6-DOF robotic manipulator

### Software
- Verilog HDL
- MATLAB
- QuIK Inverse Kinematics Solver
- Python (training and validation)

## Related Work

Li, Y., Li, L., and Choset, H., *FPGA Acceleration for High-Dimensional Inverse Kinematics* (ShanghaiTech University / Carnegie Mellon University).

This project extends prior FPGA-based inverse kinematics acceleration research by exploring neural-network inference as an alternative approach to conventional analytical and Jacobian-based inverse kinematics methods, with a particular focus on real-time robotic control applications.
