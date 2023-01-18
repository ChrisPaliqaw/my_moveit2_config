# my_moveit2_config
MoveIt2 package for The Construct's Master Class Phase 2

First review instructions from [ur3e_moveit_configB](https://github.com/ChrisPaliqaw/ur3e_moveit_configB)

in `rviz` shell
```
ros2 launch my_moveit2_config my_planning_execution.launch.py launch_rviz:=true
```
in `manipulation` shell
```
source ~/ros2_ws/install/setup.bash
ros2 launch moveit2_scripts test_trajectory.launch.py
```

# Manipulation: rqt
in `rqt` shell, use this to get the correct joint positioning values
```
source /opt/ros/noetic/setup.bash
rosrun rqt_joint_trajectory_controller rqt_joint_trajectory_controller
```
