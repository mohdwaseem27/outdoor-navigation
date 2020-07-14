# outdoor-navigation

## to bring up the model in gazebo 


`roslaunch sk bringup.launch`

## to bring up the model with willowgarage in gazebo 

`roslaunch sk sk.launch`


## for out door autonomous navigation


`roslaunch sk_navigation gps_nav.launch`


After launching gps_nav, we can now give the goal globally using 2D Nav Goal from rviz

![rviz](/home/waseem/pic.png)

Robot reaches the goal by avoiding obstacles


