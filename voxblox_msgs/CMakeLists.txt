cmake_minimum_required(VERSION 2.8.3)
project(voxblox_msgs)

find_package(catkin_simple REQUIRED)
# find_package(catkin REQUIRED COMPONENT geometry_msgs)
catkin_simple(ALL_DEPS_REQUIRED)

##########
# EXPORT #
##########

cs_install()
cs_export()
