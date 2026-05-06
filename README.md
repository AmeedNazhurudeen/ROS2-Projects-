# 🤖 ROS 2 Robotics Portfolio

This repository is a structured collection of advanced ROS 2 simulation projects designed to demonstrate core robotics concepts, system integration, and real-world applications.

The projects focus on building complete robotic pipelines—from perception and mapping to planning and control—using modern ROS 2 tools and frameworks.

---

## 🚀 Project Highlights

* 🧭 Autonomous Navigation using SLAM and Nav2
* 🤖 Industrial Robotic Arm with Vision-Based Object Manipulation
* 🌊 Underwater ROV with SLAM and Sensor Fusion
* 🚁 Drone Simulation with Planning and Control

---

## 🧠 Key Concepts Covered

* ROS 2 Nodes, Topics, Services, and Actions
* TF2 (Transform Frames)
* URDF (Robot Modeling)
* SLAM (Simultaneous Localization and Mapping)
* Navigation Stack (Nav2)
* Computer Vision with OpenCV
* Sensor Integration (LiDAR, IMU, RGB, Depth Cameras)
* Simulation using Gazebo
* Visualization using RViz2

---

## 🛠️ Tech Stack

* ROS 2 (Humble / Iron)
* Gazebo Simulator
* RViz2
* OpenCV
* Python (rclpy)
* C++ (rclcpp)

---

## 📂 Repository Structure

```
ros2-robotics-portfolio/
│
├── docs/                 # Architecture diagrams and documentation
├── common/               # Shared utilities and configurations
├── projects/
│   ├── autonomous_navigation_sim/
│   ├── industrial_arm_cv/
│   ├── underwater_rov_slam/
│   └── drone_project/
└── docker/               # Container setup (optional)
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```
git clone https://github.com/your-username/ros2-robotics-portfolio.git
cd ros2-robotics-portfolio
```

### 2. Build workspace

```
colcon build
```

### 3. Source environment

```
source install/setup.bash
```

---

## ▶️ Running Projects

Each project contains its own launch files. Example:

```
ros2 launch autonomous_navigation_sim simulation.launch.py
```

---

## 🎯 Objectives

* Develop strong understanding of ROS 2 ecosystem
* Build modular and scalable robotic systems
* Simulate real-world robotics applications
* Create a professional robotics portfolio

---

## 🔮 Future Improvements

* Multi-robot coordination
* AI-based perception models
* Real robot deployment
* Cloud-based robotics integration

---

## 📸 Visualization

* RViz2 → Real-time sensor data & robot state
* Gazebo → Physics-based simulation environment

---

## 👨‍💻 Author

Ameed

---

## 📜 License

This project is open-source and available under the MIT License.
