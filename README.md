# install-ros
**Task 1: Steps **

Step 1 — Set up ROS Noetic repo for Ubuntu

Step 2 - Add official ROS keyring

sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654

Step 3 — Update ROS package index sudo apt-get update

Step 4 — Install ROS Noetic package

sudo apt-get install ros-noetic-desktop-full • ros-noetic-desktop-full • ros-noetic-desktop • ros-noetic-ros-base • ros-noetic-ros-cor Install ros-noetic-desktop-full Includes (ros-noetic-desktop) (ros-noetic-perception) (ros-noetic-simulators) packages.

ros -noetic-desktop-full sudo apt install ros-noetic-desktop-full

Install ros-noetic-desktop Includes the following packages: • robot • vis • angles • common_tutorials • geometry_tutorials • joint_state_publisher_gui • ros_tutorials • roslint • urdf_tutorial • visualization_tutorials

to install it :

sudo apt install ros-noetic-desktop

Install ros-noetic-base:

sudo apt install ros-noetic-base

Install ros-noetic-core

Full list: • catkin • class_loader • cmake_modules • common_msgs • gencpp • geneus • genlisp • genmsg • gennodejs • genpy • message_generation • message_runtime • pluginlib • ros • ros_comm • rosbag_migration_rule • rosconsole • rosconsole_bridge • roscpp_core • rosgraph_msgs • roslisp • rospack • std_msgs • std_srvs

install ros-noetic-core:

sudo apt install ros-noetic-core sudo apt install python-rosdep python-rosinstall python-rosinstall-generator python-wstool build-essential sudo apt install python-rosdep sudo rosdep init rosdep update

git clone https://github.com/smart-methods/arduino_robot_arm.git Ros Noetic environment

Run following command: source /opt/ros/noetic/setup.bash echo "source /opt/ros/noetic/setup.bash" >> ~/.bashrc

double check: tail ~/.bashrc

verify roscore:

verify rescore

Launch: Roslaunch robot_arm_pkg check_motors.launch
