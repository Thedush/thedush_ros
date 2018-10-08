cmake_minimum_required(VERSION 2.8.3)
project(thedush_gazebo)
find_package(catkin REQUIRED COMPONENTS
  gazebo_ros
  gazebo_ros_control
  
)


catkin_package(

)

include_directories(
  ${catkin_INCLUDE_DIRS}
)
