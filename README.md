# Demo-a-simple-shop-assistant-robot
This project contains a demo of a simple shop-assistant robot, which has different modes. We use Turtlebot_2 Kobuki and Kinect v1 as our platform.
# Preparation work
  Firstly, ensure that you have correctly installed turtlebot_navigation packages, completely followed ROS Wiki and installed
PocketSphinx successfully.
# Create workspace and Catkin_make
Create a new workspace 'catkin_ws', and put all of the files into folder 'src'. Remember to change each path written in any files 
to your own path.
# Test!
Type the codes below:

roslaunch navigation_test sbfinal.launch

roslaunch speech gpsr.launch
# What will it do
If the code runs successfully, then you can choose to say: 'James, yes thank you' or 'James, no I do not need' to determine which mode will it acts. The former one will make the robot give out several questions one by one, and finally generate a recommendation list according to your answer. The latter one, robot will list all the merchandises that we have. No matter you choose which one, once you certify the very goods you want, then the robot will go to the direct shelf, pick(nope) it and go back for the next turn.
