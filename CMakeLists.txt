cmake_minimum_required(VERSION 2.8.3)
project(homework20150422)

find_package(catkin REQUIRED COMPONENTS
  std_msgs
  geometry_msgs
  turtlesim
  roseus)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES homework20150422
#  CATKIN_DEPENDS other_catkin_pkg
#  DEPENDS system_lib
)
