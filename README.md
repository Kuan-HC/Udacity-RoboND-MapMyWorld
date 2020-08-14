# ROSND Map My World
<img src="MCL2.gif"/>

The project was developed on Ubuntu 18.04 LTS with ROS Melodic, Gazebo and catkin installed.

## Dependencies for Running Locally
* ``rtabmap_ros`` ROS packages, can be install through:
``sudo apt-get install ros-melodic-rtabmap-ros``  

## Basic Build Instructions
1. Clone this repo to your work space e.g. c:/home/workspace/
2. cd /home/workspace/Udacity-RoboND-Map-My-World/
3. catkin_make

## Launch the Project
In seperate terminals:
1. cd /home/workspace/Udacity-RoboND-Where-AM-I/
2. source devel/setup.bash
 
### Launch Gazebo world, teleop and Rviz:
``roslaunch my_robot world.launch``

### Launch Rtabmap node:
``roslaunch my_robot mapping.launch``
``db`` file fill be located in the ~Udacity-RoboND-Map-My-World/src/my_robot/map
