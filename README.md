# ROS 2 Differential Drive Robot with Gazebo Simulation 🤖

This repository contains a complete ROS 2 package for an autonomous differential drive robot. The project demonstrates the integration of a custom robot description (URDF/Xacro) with Gazebo simulation and RViz visualization.

## 🎥 Project Demonstration
*(The video below shows the robot navigating a maze environment)*


<div align="center">
  <video src="https://github.com/user-attachments/assets/7828ac9c-3587-48e0-82bf-c52375fc7e3e" muted autoplay loop width="80%"></video>
</div>

## 🛠️ Tech Stack & Features
* **Framework:** ROS 2
* **Simulation:** Gazebo 
* **Visualization:** RViz
* **Robot Type:** Differential Drive Kinematics
* **Sensors:** Lidar integration for environmental mapping
* **Languages:** Python / XML (Launch files)

## 📁 Package Structure
* `my_robot_description`: Contains the URDF/Xacro files defining the robot's physical properties, joints, links, and Gazebo plugins.
* `my_robot_bringup`: Contains the launch files and configurations (including the Gazebo bridge and Maze world) to run the simulation seamlessly.

## 🚀 How to Run
1. Clone this repository into your ROS 2 workspace `src` folder.
2. Build the workspace using `colcon build`.
3. Source the setup file.
4. Launch the simulation using the provided launch file in the `bringup` package.
