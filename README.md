Step 1;
Unzip the folder and add the package to the catkin_ws
Step 2:catkin make
catkin_make clean && catkin_make
Step 3:source
source catkin_ws/devel/setup.bash
Step 4: launching in arena
roslaunch refinebot template_launch.launch
Step 5:teleop
rosrun refinebot teleop_template.py

