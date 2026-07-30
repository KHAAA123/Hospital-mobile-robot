# 🏥 Autonomous Hospital Delivery Robot

An autonomous hospital delivery robot developed using **ROS 2**, **Nav2**, and **LiDAR-based localization**. The system is designed to transport medicines safely inside hospital environments while autonomously navigating corridors, avoiding obstacles, and docking at predefined delivery stations.

---

## 📌 Features

- Autonomous navigation using ROS 2 Navigation Stack (Nav2)
- LiDAR-based SLAM and localization
- Global path planning and local obstacle avoidance
- Differential drive mobile robot
- Automatic docking at predefined locations
- Real-time obstacle detection
- Waypoint navigation
- RViz2 visualization
- Modular ROS2 architecture

---

## 🎥 Demonstration
[<-->](https://youtu.be/vAuWKDqSym8?si=12n-BMvMb81bmRIO)

## 📷 System Overview


## 🛠 Hardware

| Component | Model |
|-----------|------|
| Main Computer | Jetson Nano B01 |
| MCU | arduino |
| Motor Driver | BTS7960 |
| LiDAR | RPLidar A1  |
| Wheel Encoder | Incremental Encoder |
| Power Supply | 12V Battery |

---
## 💻 Software
- Ubuntu 22.04
- ROS 2 foxy
- Nav2
- RViz2
- Gazebo
- SLAM Toolbox
- TF2
- Python
- C++
---

## 📂 Project Structure

```text
robot_ws/
│
├── src/
│   ├── articubot_one/          # Main robot package
│   ├── diffdrive_arduino/      # Differential-drive hardware interface
│   ├── rplidar_ros/            # LiDAR driver
│   ├── csi_camera_reader/      # CSI camera interface
│   ├── ball_tracker/           # Vision-based object tracking
│   ├── serial/                 # Serial communication library
│   ├── serial_motor_demo/      # Motor communication example
│   ├── vision_opencv/          # OpenCV bridge for ROS 2
│   └── web_video_server/       # Video streaming server
│
├── .gitignore
├── LICENSE
└── README.md
```
