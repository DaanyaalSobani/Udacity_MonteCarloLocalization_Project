# Udacity_MonteCarloLocalization_Project
 The third Project in the Udacity Robotics Software Engineering Course
## Localization Screenshot
![gazeboPix](https://user-images.githubusercontent.com/22554139/127042083-8184552b-4b18-49a9-b2be-67066e4e8239.png)
![Rviz](https://user-images.githubusercontent.com/22554139/127042093-bec7acea-7fe2-4603-9f9b-7a7c071f7b94.png)
## How to use:
After cloning the repo into the src directory of a catkin_ws
1. Source the setup.bash
```
source devel/setup.bash
```

2. Launch the gazebo world and the robot.
```
roslaunch my_robot world.launch
```

3. Launch the navigation stack.
```
roslaunch main amcl.launch
```

4. Set navigation goal using teleop or 2D nav-goal in Rviz
