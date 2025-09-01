cmake_minimum_required(VERSION 3.14)
project(tinyPLC_vehicle_description)
find_package(ament_cmake REQUIRED)
install(DIRECTORY config urdf mesh
  DESTINATION share/${PROJECT_NAME}
)
ament_package()
