cmake_minimum_required(VERSION 2.8.3)

project(thedush_robots)

find_package(catkin REQUIRED)


catkin_package(
  CATKIN_DEPENDS urdf xacro
)

include_directories(${catkin_INCLUDE_DIRS})

install(
  DIRECTORY launch meshes urdf robots vrep
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)