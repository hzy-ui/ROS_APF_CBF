# ROS_APF_CBF

### The source code for CBF parameters updated algorithm in control framework.
###### The simulation is performed in Gazebo/ROS (Melodic) environment which runs in Linux (Ubuntu 18.04)

### launch 
* For the control framework with CBF parameters updated algorithm 
```
roslaunch uav_planning task_achievement.launch 
```
###### Please uncomment some code if input constraint is required

* For the control framework without CBF parameters updated algorithm 
```
roslaunch uav_planning task_achievement_no_update.launch
```
