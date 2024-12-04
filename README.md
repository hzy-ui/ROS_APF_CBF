# ROS_APF_CBF

### The source code of proposed CBF-APF based controller incorporated with online tuning CBF approach.
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
### Video
[Simulation Video](https://vimeo.com/869509705?share=copy).

### Update log
catkin_ws_1006: add object-oriented approach for multi-agent work later (scripts/test_obj)
