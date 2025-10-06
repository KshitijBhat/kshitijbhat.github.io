---
title: Autonomous Dual-Arm Bell Pepper Harvesting Robot
summary: End-to-end perception and pose estimation pipeline for autonomous agricultural manipulation using dual-arm robotics.
tags:
  - Computer Vision
  - Robotics
  - Deep Learning
  - ROS 2
date: '2024-09-01T00:00:00Z'

external_link: 'https://mrsdprojects.ri.cmu.edu/2025teame/'

image:
  caption: Bell pepper harvesting with dual-arm robot
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Code
    url: 'https://github.com/VADER-CMU/pose_estimation'
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

slides: ""
---

Developed under Dr. Nancy Pollard at Carnegie Mellon University, this project focuses on creating an autonomous robotic system for agricultural harvesting applications.

## Key Achievements

**Advanced Perception Pipeline**: Architected a comprehensive end-to-end perception system for autonomous bell pepper detection and segmentation. This included curating and augmenting a custom dataset, then training a YOLOv8 segmentation model that achieved impressive performance metrics of 92.5% mAP@50 and 86% recall, enabling reliable fruit identification in cluttered agricultural environments.

**High-Precision 3D Pose Estimation**: Designed and implemented a custom coarse-to-fine pose estimation pipeline utilizing RGB-D camera data to compute accurate 6-DOF poses of bell peppers. The system achieves sub-3 cm positional accuracy and orientation errors under 10 degrees, providing the precision necessary for successful robotic grasping and manipulation of delicate produce.

## Technical Stack

- ROS 2 for robot middleware and communication
- YOLOv8 for real-time object detection and segmentation
- RGB-D sensing for depth perception
- Custom pose estimation algorithms for manipulation planning

This project demonstrates the integration of modern deep learning techniques with classical robotics approaches to solve challenging real-world agricultural automation problems.