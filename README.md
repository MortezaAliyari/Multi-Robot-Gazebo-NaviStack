# Multi-Robot-Gazebo-NaviStack
This repo relate to multi mobile robots in Gazebo simulator. Based on Navigation stack packages, environment map is created and each robot is able to do motion planning. **Enter**
---
If you like the project give me a star! :star: 

You can see the video: &nbsp;&nbsp;
[![website](./img/youtube-dark.svg)](https://www.youtube.com/watch?v=XaLbEKf8UhA)
&nbsp;&nbsp;
---

'''
source /opt/ros/noetic/setup.bash
cd catkin_ws
wget https://gist.githubusercontent.com/airuchen/5e58eb5dc54d6dc38ea5d2bedd53f69e/raw/ae3b850aca5a0577105c682eec1ab3b534161cc2/multi_omnibot.repos
vcs import src/ < multiple_turtlebot3_env.repos
catkin_make
source devel/setup.bash

'''






