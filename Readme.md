ROS1 Noetic ros_lib from rosserial

sudo apt-get -y install ros-noetic-rosserial-arduino ros-noetic-rosserial
mkdir arduino
cd arduino
rosrun rosserial_arduino make_libraries.py .

Copy ros_lib