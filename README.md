# sensor_fusion_cg

* [ethzasl_sensor_fusion](http://wiki.ros.org/ethzasl_sensor_fusion): Time delay compensated single and multi sensor fusion framework based on an EKF
* [ethzasl_sensor_fusion Tutorials](http://wiki.ros.org/ethzasl_sensor_fusion/Tutorials)
* [robot_localization wiki](http://docs.ros.org/melodic/api/robot_localization/html/)
* [Sensor Fusion and Tracking Toolbox (mathworks)](https://www.mathworks.com/products/sensor-fusion-and-tracking.html)

-----

[TOC]

# Code

## Install & Build

* install dependencies
  ```sh
  wstool init src/ src/dependencies.rosinstall
  ```

* build
  ```sh
  catkin build
  ```

# Docs

## Methods Overview

<div align=center>
  <img src="./images/sensor_fusion_methods.jpg">
</div>

## Kalman Filter

* [WTF is Sensor Fusion? The good old Kalman filter](https://towardsdatascience.com/wtf-is-sensor-fusion-part-2-the-good-old-kalman-filter-3642f321440)
* [IMU-sensor-fusion-with-linear-Kalman-filter (mathworks)](https://www.mathworks.com/matlabcentral/fileexchange/70093-imu-sensor-fusion-with-linear-kalman-filter)
