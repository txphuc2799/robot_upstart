robot_upstart [![Build Status](https://travis-ci.org/clearpathrobotics/robot_upstart.svg?branch=jade-devel)](https://travis-ci.org/clearpathrobotics/robot_upstart)
=============

Clearpath Robotics presents a suite of scripts to assist with launching background ROS processes on Ubuntu Linux PCs. Please see the [generated documentation](http://docs.ros.org/latest-available/api/robot_upstart/html/) and [ROS Wiki](http://wiki.ros.org/robot_upstart).

### Usage:
rosrun robot_upstart install pkg_name/launch/file_name.launch --job executive_name --user user_name --logdir path_to_log --setup ~/catkin_ws/devel/setup.bash --symlink
