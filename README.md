# Attitude Estimation of an Aerial Vehicle Using Sensor Data Fusion
Overview
This project involves estimating the 3D orientation of an aerial vehicle using data from a 6-DoF IMU sensor and comparing it with ground truth from a Vicon motion capture system. The project is divided into two phases:

Phase 1 - IMU Attitude Estimation
We use data from a 3-axis gyroscope and a 3-axis accelerometer to estimate orientation. Methods include:

Gyroscope-Based Estimation: Computes orientation from gyro data.
Accelerometer-Based Estimation: Computes orientation from accelerometer data.
Complementary Filter: Combines gyro and accelerometer data for improved accuracy.
Phase 2 - Waypoint Navigation and AprilTag Landing (Placeholder)
Design and implement a navigation system for a simulated quadrotor to navigate to waypoints and land on an AprilTag.

Code Structure
main.ipynb: Implements the orientation estimation algorithms for Phase 1.
Results
Combined Results


Gyroscope-Based Orientation


Accelerometer-Based Orientation


Complementary Filter Orientation


References
IMU Sensor Data
Ground Truth Data
