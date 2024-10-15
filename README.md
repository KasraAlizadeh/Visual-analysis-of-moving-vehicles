# 🚗 Visual Analysis of Moving Vehicles

This repository contains the final project for the **Image Analysis and Computer Vision course** at *Politecnico di Milano*. The project focuses on the visual analysis of moving vehicles, leveraging the [KITTI Dataset](https://www.kaggle.com/datasets/klemenko/kitti-dataset) to explore and implement techniques for vehicle detection, motion tracking, and environmental interaction analysis.

## 📜 Project Overview

### Problem Statement

Autonomous driving necessitates accurate detection, localization, and analysis of moving vehicles to ensure safety and efficiency. This project aims to utilize computer vision and image analysis techniques to study moving vehicles, their trajectories, and interactions with their environment. Specifically, the project covers:

- **Vehicle Detection**: Identifying and counting vehicles in each frame.
- **Trajectory Estimation**: Tracking vehicle movement over time to estimate paths and predict future locations.
- **Speed Calculation**: Estimating vehicle speed using frame-by-frame displacement.
- **Ego-motion and Environment Analysis**: Understanding the movement of the camera (vehicle) and analyzing the relative motion of other objects in the scene.

### Dataset

The project utilizes the **KITTI Dataset**, a well-known benchmark in the field of computer vision that includes:

- **Camera Images**: High-resolution images from the front camera, suitable for vehicle detection and tracking.
- **LiDAR Data**: 3D point cloud data for detailed spatial analysis.
- **Ground Truth Annotations**: Labeled data for various objects, including vehicles, pedestrians, and cyclists.
- **Calibration Data**: Metadata containing camera calibration parameters for accurate mapping between 2D images and 3D space.

The KITTI dataset enables detailed exploration of both 2D and 3D visual analysis for vehicle detection and tracking, providing a robust foundation for developing and testing various computer vision algorithms.
