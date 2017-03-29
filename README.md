# Didi-Challenge

#![Alt text](didi_challenge_dataset.gif?raw=true "Optional Title")

This is the repository for the Didi/Udacity challenge of the Italian Verona team.

Install ROS http://www.ros.org/ 

Create a catkin workspace http://wiki.ros.org/catkin/Tutorials/create_a_workspace

Be sure to have your build-essential "sudo apt-get update && sudo apt-get install build-essential"

enter in your catkin worspace "cd catkin_ws"

be sure to have all the rosdep "rosdep install --from-paths src --ignore-src --rosdistro indigo"

catkin_make

In order to launch the visualization you should refer to the launchPKG and you should download and play the rosbag from here: https://drive.google.com/file/d/0B3n4hbrsMGiZQ1c5M2wybGNIZjg/view?usp=sharing

Launch the roslaunch comand and specify the pat on your rosbag folder: "roslaunch launchPKG display_rosbag_rviz.launch rosbag_file:=/path/approach_1.bag" 









