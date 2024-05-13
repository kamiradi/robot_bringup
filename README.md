# Real Robot bringup

This repository acts as the one stop solution to run real robot scripts.

## Running the robot
The following launch file is my workhorse for the robot. It runs the following:
- `serl` impedance controller
- `spacenav_node` to launch the spacenav 
- `space_teleop` node for the teleoperation

```
roslaunch robot_bringup robot_bringup.launch
```
