# AI-Second-task
ROS_Arm_Package_Installation
Download and install Arduino robot arm packages.

Step 1: create a new directory and install the catkin tool.

mkdir -p ~/catkin_ws/src ==> cd ~/catkin_ws/ ==> catkin_make

Step 2: Install packages.

1- cd ~/catkin_ws/src

2- sudo apt-get install ros-noetic-moveit

3- sudo apt-get install ros-noetic-joint-state-publisher ros-noetic-joint-state-publisher-gui

4- sudo apt-get install ros-noetic-gazebo-ros-control joint-state-publisher

5- sudo apt-get install ros-noetic-ros-controllers ros-noetic-ros-control

Step 3: While running ROS on a different terminal enter the lines below.

1- cd ~/catkin_ws

2- catkin init

3-catkin_make

4-git clone https://github.com/smart-methods/arduino_robot_arm

5-source /home/saud/catkin_ws/devel/setup.bash

6-roslaunch robot_arm_pkg check_motors.launch
