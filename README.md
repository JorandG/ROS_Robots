# ROS_Robots
This repo aims to create a package to control a TurtleBot 2e and the Widowx MKII with differents sensors on ROS Noetic.

# Table of Contents

- [Turtlebot](#turtlebot)
- [Widowx](#widowx)
- [Installation](#installation)

# Recommended OS/Programs
The pacakge was developped and tested on:

• Ubuntu 20.04 LTS

• ROS Noetic

• MoveIt! for ROS Noetic

# Turtlebot

The robot used for this package is the TurtleBot2 which is an open hardware robot developped at Willow Garage by Melonee Wise and Tully Foote in November 2010:
<img width="677" alt="Turtlebot" src="https://www.turtlebot.com/assets/images/turtlebot_2_lg.png">


  
# Widowx

The WidowX Robot Arm Mark II is developped by Interbotix Labs' offering for the MX series of DYNAMIXEL Servos:
  
  <img width="677" alt="Widowx" src="https://www.trossenrobotics.com/images/PImages/widowx-a.jpg">

## Usage

To launch moveit and start planning the robot use the command

``` roslaunch widowx_arm_bringup arm_moveit.launch```

Check if the port used for the robot is ttyUSB0 in case of problems. 
  
 # Installation
 
 To install the current version of the repository to your machine, change directory into the desired catkin workspace source directory, and clone the repository. After this, build the code using  ``` catkin_make``` in the workspace directory. 

# License

For the section on the Widowx arm, this repository is an adaption on ROS Noetic of Interbotix's [Widowx repository](https://github.com/Interbotix/widowx_arm). Copyright for these are held by others, as reflected in the commit history for the original files.
The arobotix_ros is modified version of the [arobotix_ros](https://github.com/Interbotix/arbotix_ros) repository.



