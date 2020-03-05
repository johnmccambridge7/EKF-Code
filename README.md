# COSC 69 Final Project: Extended Kalman Filter with Visual Feature Tracking using AR Tags
### Winter 2020
###  Janvi Kalra, John McCambridge, Rylee Stone

## Description:
This project is split among 6 files in the EKF `src` folder. The primary code driver is `RobotController.py` which implements methods from most of the other included files. `GUI.py` is used to drive a robot for data to store in a bag file for analysis. Similarly, `robo_path.py`   is a script used for data collection and drives the bot over a pre-determined path. 

## How to Run the Program:
This program is currently set up to simply be executed by running the `RobotController.py` file. Note that this file should be executed before attempting to begin publishing messages intended for the EKF (i.e. if planning to perform the test on a bag file, the node for `RobotController.py` should be initialized before trying to run the bag file). No additional commands or input needed, but messages must be being published when the program is run. 

## Authors:
Janvi Kalra
John McCambridge
Rylee Stone
