# OpenCV-in-ROS-Noetic
Learn the basics of how to interface ROS with OpenCV

mkdir -p ~/catkin_ws/src  
cd ~/catkin_ws/src  
git clone https://github.com/hussains72/OpenCV-in-ROS-Noetic.git  
cd ..  
source devel/setup.bash  
roscd cv_basics/src  
cd ~/catkin_ws  
catkin_make  
rosrun image_view image_view image:=/camera  
roslaunch cv_basics cv_basics_cpp.launch
