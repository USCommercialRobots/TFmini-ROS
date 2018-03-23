# TFmini-ROS
TFmini's Examples for ROS.  

```c
/**************************************************************************************************************************************
/* Benewake mini infrared range sensor TFmini ROS package
/* Version 1.0
/**************************************************************************************************************************************

/**************************************************************************************************************************************
/* Package Information
/**************************************************************************************************************************************
  Package:			tfmini_ros
  Node:				tfmini_ros_node
  Published Topics:
    /tfmini_ros_node/TFmini (sensor_msgs/Range)
      The distance of object detected. 
      Note: This node won't publish topic if no object exists within TFmini's measurement range, and the behavior can be changed in file 
      /src/TFmini_ros_node.cpp
      
/**************************************************************************************************************************************
/* Quick Start
/**************************************************************************************************************************************
  $ roslaunch tfmini_ros tfmini.launch
```
