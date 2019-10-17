cmake_minimum_required(VERSION 3.5)
project(fetch_description)

find_package(ament_cmake REQUIRED)
find_package(urdf REQUIRED)

install(DIRECTORY meshes robots
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
