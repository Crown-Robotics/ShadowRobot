# ShadowRobot
Documentation and source code to control https://www.shadowrobot.com/dexterous-hand-series/

## TODO
1) Update "ROS_DOMAIN_ID" variable https://docs.ros.org/en/humble/Tutorials/Beginner-CLI-Tools/Configuring-ROS2-Environment.html#the-ros-domain-id-variable



## Key ROS 2 Features to understand
1) Domain ID's: https://docs.ros.org/en/humble/Concepts/Intermediate/About-Domain-ID.html
2) TBD <br> <br>


## TurtleSim to Crown Setup Steps
1) At least two shells open for running and controlling 
2) Use "rqt &" command in 3rd shell to start RQT application
3) Change tele-op with "ros2 run turtlesim turtle_teleop_key --ros-args --remap turtle1/cmd_vel:=T3/cmd_vel" in 3rd shell <br> <br>
