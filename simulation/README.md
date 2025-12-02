# Simulation

This folder contains the **Gazebo–ROS simulation setup** for the paper  
*“Finite-Time Trajectory Tracking of a Four Wheeled Mecanum Robot”*.

Planned structure:

- `controllers/` – ROS nodes / Python scripts implementing  
  - finite-time backstepping controller  
  - asymptotic controller (for comparison)
- `launch_files/` – ROS launch files to start Gazebo, spawn the robot,  
  and run the controllers.
- `urdf/` – Robot description (URDF/Xacro) and related mesh files.

Code and configuration files will be added here gradually as the project is cleaned up and organised.
