cmake_minimum_required(VERSION 2.8.3)
project(little_pig_rviz)

find_package(catkin REQUIRED)
catkin_package()

install(DIRECTORY launch rviz
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
