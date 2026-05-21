cmake_minimum_required(VERSION 3.8)
project(my_robot_bringup)

find_package(ament_cmake REQUIRED)

# Install launch files
install(
  DIRECTORY launch
  DESTINATION share/${PROJECT_NAME}/
)

# Install Gazebo world files
install(
  DIRECTORY worlds
  DESTINATION share/${PROJECT_NAME}/
)

# Install bridge config
install(
  DIRECTORY config
  DESTINATION share/${PROJECT_NAME}/
)

# Install RViz config (optional)
install(
  DIRECTORY rviz
  DESTINATION share/${PROJECT_NAME}/
  OPTIONAL
)

ament_package()
