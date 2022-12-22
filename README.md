#RefineBot - The Toy Car (ROS Melodic)

###Steps:
- Step 1:
Unzip the folder and add the package to the catkin_ws

- Step 2:catkin make
```
catkin_make clean && catkin_make
```

- Step 3:source your workspace
```
source catkin_ws/devel/setup.bash
```

- Step 4: launching the bot
```
roslaunch refinebot template_launch.launch
```

- Step 5: Operating the bot, P.s make sure your source the new terminal before using teleop
```
rosrun refinebot teleop_template.py
```
