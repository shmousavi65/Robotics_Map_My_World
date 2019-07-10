# Robotics_Localization_with_Adaptive_Monte_Carlo

This project exploits Adaptive Monte Carlo algorithm to localize a robot in a predfined environment.

## Execution
Create the required directories for the workspace:
```
mkdir -p catkin_ws/src
```
Initialize the workspace and clone this repository:
```
cd catkin_ws/src
catkin_init_worksapce
git clone https://github.com/shmousavi65/Robotics_Localization_with_Adaptive_Monte_Carlo.git
```
Build the project:
```
cd ..
catkin_make
```
Source the setup file:
```
source devel/setup.bash
```
Run the gazebo_world related nodes:
```
roslaunch my_robot world.launch
```
Run the Adaptive MCL launch file:
```
roslaunch my_robot amcl.launch 
```
In order to navigate the robot through the environment run the teleop node by following command:
```
rosrun teleop_twist_keyboard teleop_twist_keyboard.py
```

Here are some screenshots from the implementation:

![](https://github.com/shmousavi65/Robotics_Localization_with_Adaptive_Monte_Carlo/blob/master/Capture1.PNG)

![](https://github.com/shmousavi65/Robotics_Localization_with_Adaptive_Monte_Carlo/blob/master/Capture2.PNG)

![](https://github.com/shmousavi65/Robotics_Localization_with_Adaptive_Monte_Carlo/blob/master/Capture3.PNG)
