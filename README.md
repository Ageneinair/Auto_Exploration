# Auto_Exploration
This is a ROS package to make the robot mapping whole environment automatically, developed by [gmapping](http://wiki.ros.org/gmapping) and [navigation_stack](http://wiki.ros.org/navigation).


## Install Related Package

```
  sudo apt-get install ros-kinetic-gmapping
  sudo apt-get install ros-kinetic-navigation
```

## Usage

```
roslaunch mbot_gazebo view_mbot_with_laser_kinect.launch
roslaunch mbot_navigation exploring_slam_demo.launch
rosrun  mbot_navigation exploring_slam.py
```

## Demo
All tasks are tested by a self-defined robot in a customized apartment in GAZEBO.

If you want to see the whole test environment, you can check [Homebot](https://github.com/Ageneinair/Homebot).


__**Click**__ below image you can see the robot explor and map the apartment automatically.

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/DRGliFoOi40/0.jpg)](https://www.youtube.com/watch?v=DRGliFoOi40)



