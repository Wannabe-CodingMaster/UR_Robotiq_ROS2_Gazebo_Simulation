# UR_Robotiq_ROS2_Gazebo_Simulation
Gazebo Classic Simulation of Universial Robot + Robotiq 2f-85.

## Used version
![Static Badge](https://img.shields.io/badge/ROS-Humble-green)
![Static Badge](https://img.shields.io/badge/Gazebo-Classic_(11)-green)

## Running Simualtion
```
ros2 launch ur_gripper_gazebo gazebo.launch.py
```
[rqt_joint_trajectory_publisher](https://github.com/Wannabe-CodingMaster/rqt_joint_trajectory_publisher) was used to control robot on this screencast.

[Screencast](https://github.com/Wannabe-CodingMaster/ur_robotiq_gazebo_simulation/assets/107594042/e4aa9948-a13a-4e62-9cee-1e25c578123b)

## Source
ur_description &rarr; [UniversalRobots](https://github.com/UniversalRobots/Universal_Robots_ROS2_Description)

robotiq_description &rarr; [PickNikRobotics](https://github.com/PickNikRobotics/ros2_robotiq_gripper/tree/main/robotiq_description)
