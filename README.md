# Robotics-Arm-Surgery-
# Surgical Robotic Arm Simulation using MATLAB

This repository contains a basic simulation of a surgical robotic arm developed using MATLAB. The project aims to model and simulate a robotic manipulator capable of performing precise movements, which are fundamental to robotic-assisted surgical procedures. The simulation focuses on the kinematic modeling of a multi-degree-of-freedom (DOF) arm, with visual representation and basic control features implemented using core MATLAB functions.

## Project Features

The project includes simulation of either a 3-DOF or 6-DOF robotic arm, providing a foundation for further development in surgical robotics. The current implementation supports forward kinematics for positional calculation, and optional inverse kinematics logic can be added for precise end-effector control. A graphical representation of the robotic arm is displayed using MATLAB’s plotting functions. Users can modify link lengths and joint angles to observe the resulting changes in the arm’s configuration.

## Tools and Technologies

This simulation is built entirely using MATLAB. Optionally, Simulink and Simscape Multibody can be integrated for more advanced modeling and physics-based simulation. The project is compatible with MATLAB R2021a or later.

## Project Structure

The repository is organized as follows:

- `main.m`: The main script that initializes parameters and runs the simulation.
- `forward_kinematics.m`: Function to compute the position of the end-effector using joint angles.
- `inverse_kinematics.m`: (Optional) Function to calculate joint angles for a given target position.
- `plot_robot.m`: Function to visualize the robotic arm in a 3D coordinate space.
- `docs/`: Contains relevant documentation or references.
- `README.md`: This file, describing the project in detail.

<img width="669" alt="image" src="https://github.com/user-attachments/assets/fe43eca4-3045-4186-bea6-bbe124d31523" />

<img width="551" alt="image" src="https://github.com/user-attachments/assets/7eb8d811-27c4-4162-ae1b-f027932b4320" />

<img width="1104" alt="image" src="https://github.com/user-attachments/assets/c6035459-2771-441e-92d2-075338a70348" />

<img width="1105" alt="image" src="https://github.com/user-attachments/assets/a954de52-6b70-4245-bc0e-1df550f1b871" />

<img width="845" alt="image" src="https://github.com/user-attachments/assets/3e4e4caf-d4b5-4894-aaee-44f1628ebf0a" />

<img width="780" alt="image" src="https://github.com/user-attachments/assets/50d83754-cd42-4065-b65f-f36d5084dc3d" />

<img width="412" alt="image" src="https://github.com/user-attachments/assets/14471417-cdc8-4002-83a8-d772c5b27a04" />


<img width="998" alt="image" src="https://github.com/user-attachments/assets/2dc144c0-0ba6-4976-94e0-85195839e7c3" />




## Getting Started

To run the simulation, clone this repository and open the project in MATLAB. Execute the `main.m` script to start the simulation. Users can adjust parameters such as joint angles and link lengths directly in the script to explore different arm configurations.

## Future Work

Future enhancements to this project may include the integration of Simscape Multibody for a more realistic simulation environment, implementation of haptic feedback or joystick control for manual operation, and connectivity with external platforms such as ROS for hardware control. Additional features may also involve path planning algorithms for surgical task automation.

## References

The development of this project is guided by resources such as the MATLAB Robotics Toolbox by Peter Corke, and literature including "Robot Modeling and Control" by Spong, Hutchinson, and Vidyasagar. MATLAB and Simulink documentation also serve as key technical references.


