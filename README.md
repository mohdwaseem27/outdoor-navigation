# outdoor-navigation

## to bring up the model in gazebo 


##### `roslaunch sk bringup.launch`

This will bringup the robot model with empty gazebo world, obstacles can be placed in between to check for the obstacle avoiding and path planning algorithm.


## to bring up the model with willowgarage in gazebo 

##### `roslaunch sk sk.launch`

This will bringup the robot model with willowgarage world, robot will navigate through the willowgarage according to the goal given from rviz and plan the plan the path accordingly

![gazebo](https://github.com/mohdwaseem27/outdoor-navigation/blob/master/docs/pic0.png) 



## for out-door autonomous navigation


##### `roslaunch sk_navigation gps_nav.launch`


After launching gps_nav, we can now give the goal globally using 2D Nav Goal from rviz

Below image shows the navigation in an empty world with some obstacles.

![rviz](https://github.com/mohdwaseem27/outdoor-navigation/blob/master/docs/pic.png)

Robot reaches the goal by avoiding obstacles.

robot is navigated without any preloaded map.


## For navigation using waypoints

##### `roslaunch sk_navigation send_goals.launch`

The waypoints are given by the file, the robot will navigate to the goal by the gps coordinates given in the file.


Thanks to [https://github.com/ArghyaChatterjee] for creating waypoints



