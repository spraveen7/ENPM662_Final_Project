# ENPM662_Final_Project
For Launching the Cart with the arm:
Launch the template_launch.launch file. This will launch the robot along with the arm attached to it.
To control the cart, launch the teleop_template.py file.

In this stage we were not able to spawn the cart properly due to the weight and size of the arm. Hence controlling the cart is also an issue.


The pick and place operation is acheived by following commands. This will only spawn the arm and not the cart.

1) perform catkin_make and devel the source
2) cd to the scripts directory, src/cartf/scripts/
3) run the command ./safe_spawner.sh
4) In a seperate terminal again cd to scripts directory, src/cartf/scripts/
5) Run the command, rosrun cartf IK_server.py
