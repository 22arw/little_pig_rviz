# Little Pig RVIZ - ROS Package

This repository is meant for all the RVIZ based code **only**. Example's of such:
- Creating a launch file for RVIZ to see RPLIDAR data simulated/real.

### Installation instructions

Heres a simple guide to get you started with Little Pig RVIZ. Before continuing, be sure to have ROS Melodic installed.

- **Step 1.**
  - ```cd catkin_ws/src```
- **Step 2.**
  - ```git clone https://github.com/22arw/little_pig_rviz.git```
  - If you don't have the other three packages you can run these lines also:
    - ```git clone https://github.com/22arw/little_pig_ctrl.git```
    - ```git clone https://github.com/22arw/little_pig_description.git```
    - ```git clone https://github.com/22arw/little_pig_gazebo.git```

Your resulting directory should have this layout:

- catkin_ws/
  - src/
    - little_pig_ctrl/
    - little_pig_description/
    - little_pig_gazebo/
    - little_pig_rviz/

### Usage Instructions

Once you have this repo downloaded, run the following commands in the terminal:

- ```cd ..```
- ```catkin_make```

This should completed without failing. If it does fail, call Coach. From the ```catkin_ws/``` directory run this:

- ```roslaunch little_pig_rviz basic_pig.launch```

You should see an rviz window open with a grid and Basic Pig just sitting there. A secondary window opens with rviz. You should be able to click on you task bar to bring it forward. This will have some UI sliders that you can play with to alter the joints on Basic Pig. If it fails, Call Coach.

