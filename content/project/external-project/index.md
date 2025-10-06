---
title: Design of a 4-Wheel Steering and Driving Mobile Robotic Platform
summary: Multi-sensor fusion framework for improving localization accuracy in four-wheel steering mobile robots.
tags:
  - Robotics
  - State Estimation
  - Sensor Fusion
  - ROS
date: '2023-05-01T00:00:00Z'

external_link: ''

image:
  caption: Four-wheel steering robot platform
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Code
    url: ''
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

slides: ""
---

Conducted at Lakehead University, Ontario, this research project focused on enhancing the localization capabilities of a four-wheel steering (4WS) mobile robot through advanced sensor fusion techniques.

## Project Overview

**Sensor Fusion Implementation**: Developed and deployed a ROS-based Extended Kalman Filter (EKF) that intelligently fuses data from multiple sensor modalities including wheel odometry, Inertial Measurement Unit (IMU), and GPS. This multi-sensor approach significantly improved the robot's state estimation accuracy.

**Performance Validation**: The implemented EKF system achieved a substantial improvement in localization accuracy, reducing the Absolute Trajectory Error (ATE) by up to 1 meter compared to single-sensor approaches. The system was rigorously validated through both real-world experiments and Gazebo simulation environments, confirming the accuracy of the kinematic and odometry models.

## Technical Implementation

- Extended Kalman Filter for non-linear state estimation
- Multi-rate sensor fusion (odometry, IMU, GPS)
- ROS ecosystem for modular software architecture
- Gazebo simulation for validation and testing
- Kinematic modeling for 4WS platforms

This project showcases the importance of probabilistic state estimation and sensor fusion in achieving robust robot localization, particularly for complex mobile platforms with four-wheel steering kinematics.
