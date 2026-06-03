# Checkpoint 15 — ROS 2 Control RB-1

This repository contains the Checkpoint 15 project for integrating ROS 2 Control with the RB-1 robot model in Gazebo Sim.

## Project goal

The goal of this project is to control the RB-1 robot through the ROS 2 Control framework instead of using independent Gazebo-only control plugins.

The project includes:

- ROS 2 Control integration for the RB-1 differential-drive base
- Controller configuration for wheel actuation
- ROS 2 Control integration for the RB-1 elevator/lifting unit
- Controller configuration for elevator actuation
- Launch and verification instructions for Gazebo Sim

## Repository structure

```text
.
├── rb1_ros2_description/   # RB-1 robot description, launch files, meshes, worlds, and Xacro/URDF files
├── robotnik_sensors/       # Sensor description/support package
└── README.md               # Repository-level project overview