# ROS2-AMR-Warehouse-Robot-
Description (short): 🚙 ROS 2 package for AMR robot simulation with URDF, Gazebo, RViz, LiDAR, and SLAM support.  Tags: ros2 gazebo rviz slam lidar robotics agv urdf navigation
# 🚙 bcr_bot – ROS 2 AGV Simulation

This repository contains the **AMR_bot** package, a mobile AGV (Automated Guided Vehicle) robot simulation developed in **ROS 2**.  
It is designed for navigation, mapping, and testing in **Gazebo** and **RViz**.  

---

## 📌 Features
- URDF model of an AGV robot  
- Launch files for Gazebo & RViz  
- LiDAR integration for mapping and navigation  
- SLAM support for map building  
- Modular structure to extend with controllers, navigation stack, etc.  

---

## 📂 Repository Structure
AMR_bot/
├── launch/ # Launch files for Gazebo, RViz, SLAM
├── urdf/ # Robot model (URDF, meshes, sensors)
├── worlds/ # Gazebo worlds
├── config/ # Navigation / SLAM configs
├── rviz/ # RViz visualization configs
└── CMakeLists.txt # Build instructions
---

## ⚙️ Installation

### 1. Clone the Repository
```bash
cd ~/agv_ws/src
git clone https://github.com/username/AMR_bot.git
cd ~/agv_ws
colcon build
source install/setup.bash
