cmake_minimum_required(VERSION 3.0.2)
project(wifibot_arm_description)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY urdf xacro rviz launch meshes
   DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

