# 🚗 Visual Analysis of Moving Vehicles

This repository contains the final project for the **Image Analysis and Computer Vision course** at *Politecnico di Milano*. The project is based on visual analysis of moving vehicles, leveraging the [Waymo Open Dataset](https://waymo.com/open) to explore and implement techniques for vehicle detection, motion tracking, and analysis of their environment.



## 📜 Project Overview

### Problem Statement

Autonomous driving requires accurate detection, localization, and analysis of moving vehicles to ensure safety and efficiency. This project focuses on using computer vision and image analysis techniques to study moving vehicles, their trajectories, and environmental interactions. Specifically, the project covers:
- **Vehicle Detection**: Identifying and counting vehicles in each frame.
- **Trajectory Estimation**: Tracking vehicle movement over time to estimate paths and predict future locations.
- **Speed Calculation**: Estimating vehicle speed using frame-by-frame displacement.
- **Ego-motion and Environment Analysis**: Understanding the movement of the camera (vehicle) and analyzing the relative motion of other objects in the scene.

### Dataset

The project utilizes the **Waymo Open Dataset**, which is a large-scale autonomous driving dataset containing:
- **LiDAR data**: 3D point cloud data for spatial analysis.
- **Camera images**: High-resolution images from multiple camera views (front, side, and rear).
- **Bounding box annotations**: Labeled objects such as vehicles, pedestrians, cyclists, etc.
- **Metadata**: Details like timestamp, camera calibration, and frame information.

Waymo's dataset allows detailed exploration of both 2D and 3D visual analysis for vehicle detection and tracking.


