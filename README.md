# DYNAVINS_ROS2
ROS2 package for dynaVINS

## Prerequisites
- Prefer to the below:
  - Ubuntu 20.04
  - ROS2 foxy
  - OpenCV 4.2.0

## How to build
Clone repository to your ROS workspace
- mkdir -p colcon_ws/src
- cd ~/colcon_ws/src
- git clone https://github.com/maekjuplease/DYNAVINS_ROS2.git
- colcon build --symlink-install

## How to use
Please refer to the following command:
ros2 runa dynaVINS 

## Acknowledgments
This repository is modified from [this](https://github.com/url-kaist/dynaVINS) repository. 
- Thank you Seungwon Song and Hyungtae Lim for making this incredible work.
