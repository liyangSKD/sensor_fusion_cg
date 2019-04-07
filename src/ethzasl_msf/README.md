# ethzasl_msf_cg

Modified version of **[ethzasl_msf](https://github.com/ethz-asl/ethzasl_msf)** (commit 5d91612  on May 1, 2018), a sensor fusion framework based on an Extended Kalman Filter (EKF) for 6DOF pose estimation including intrinsic and extrinsic sensor calibration.

* MSF: Modular framework for multi sensor fusion based on an Extended Kalman Filter (EKF)
* Wiki: https://github.com/ethz-asl/ethzasl_msf/wiki
* API: http://ethz-asl.github.io/ethzasl_msf
* Paper
  ```
  @INPROCEEDINGS{lynen13robust,
     Author = {S Lynen and M Achtelik and S Weiss and M Chli and R Siegwart},
     Title = {A Robust and Modular Multi-Sensor Fusion Approach Applied to MAV Navigation},
     Booktitle = {Proc. of the IEEE/RSJ Conference on Intelligent Robots and Systems (IROS)},
     Year = {2013}
  }
  ```

-----

# Docs

* `doxygen msf_dox.dox`

# TODO

* Multiple fuzzy tracking states
* extern templates c++11
* Eigen::Map wrap Q-blocks (if possible)
* Multiplication of F blockwise
* Obs-constrainted EKF prediction
* symm P: EV decompose P, set EVs<eps to zero and rebuild (profile this to know the cost!)
* make sensor_manager provide interface to add measurement to core, so that measurements dont need to include the core, but just the base manager class.
* use more polymorphism to reduce compilation time and break up dependencies
* plot_scripts autogen with correct indices from msf_core
* TRUE MODULARITY:
  - template sensors to calibration states
  - Every sensor has a set of states (calib bias etc) these get added to a large state vector automatically.
