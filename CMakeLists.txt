cmake_minimum_required(VERSION 2.8.3)
project(erobotica_omnibot)

## Compile as C++11, supported in ROS Kinetic and newer
# add_compile_options(-std=c++11)

## Find catkin macros and libraries
## if COMPONENTS list like find_package(catkin REQUIRED COMPONENTS xyz)
## is used, also find other catkin packages

find_package(catkin REQUIRED
  gazebo
  roscpp
  rospy
  tf
  turtlesim
  tf2
  tf2_ros
  geometry_msgs
  std_msgs
  tf
  nav_msgs
  )


catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES erobotica_omnibot
#  CATKIN_DEPENDS other_catkin_pkg
#  DEPENDS system_lib
)
include_directories(
  ${catkin_INCLUDE_DIRS}
)

