# sensor_fusion_cg

* [ethzasl_sensor_fusion](http://wiki.ros.org/ethzasl_sensor_fusion): Time delay compensated single and multi sensor fusion framework based on an EKF
* [ethzasl_sensor_fusion Tutorials](http://wiki.ros.org/ethzasl_sensor_fusion/Tutorials)
* [robot_localization wiki](http://docs.ros.org/melodic/api/robot_localization/html/)
* [methylDragon/ros-sensor-fusion-tutorial](https://github.com/methylDragon/ros-sensor-fusion-tutorial): An in-depth step-by-step tutorial for implementing sensor fusion with robot_localization!
* [Sensor Fusion and Tracking Toolbox (mathworks)](https://www.mathworks.com/products/sensor-fusion-and-tracking.html)
* [locusrobotics/fuse](https://github.com/locusrobotics/fuse): The fuse stack provides a general architecture for performing sensor fusion live on a robot. Some possible applications include state estimation, localization, mapping, and calibration.

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
  catkin_make
  ```

# Docs

* [Sensor Fusion Tutorial](https://datascopeanalytics.com/blog/sensor-fusion-tutorial/)

## Methods Overview

<div align=center>
  <img src="./images/sensor_fusion_methods.jpg">
</div>

## Kalman Filter

* [WTF is Sensor Fusion? The good old Kalman filter](https://towardsdatascience.com/wtf-is-sensor-fusion-part-2-the-good-old-kalman-filter-3642f321440)
* [ROS Kalman Filter for Sensor Fusion](https://fjp.at/posts/ros/ros-kalman-filter/)

## Others

* [传感器融合：通向自动驾驶时代的关键一步](https://www.leiphone.com/news/201708/HH3MYTdsDx3mFx0S.html)
