# mobile_robot_example
This repository have a general differential mobile robot create with simple shapes, this robot have a lidar and camera sensors with their plugins for 
gazebo 11.

To use this repository remember to clone it inside your workspace (dev_ws/src) and create the directories **`worlds` `src` `config`** inside the package.

This package have 2 launch files:


-The first one it's for rviz visualization, you need to run in your terminal the command: 
~~~
ros2 launch mobile_robot_example robot_display.launch.py
~~~
-The other one it's for the gazebo simulation, you need to run in your terminal the command: 
~~~
ros2 launch mobile_robot_example robot_gazebo.launch.py
~~~
