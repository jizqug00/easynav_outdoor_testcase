cmake_minimum_required(VERSION 3.20)
project(easynav_outdoor_testcase)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

find_package(ament_cmake REQUIRED)
find_package(easynav_common REQUIRED)

install(DIRECTORY robots_params maps
  DESTINATION share/${PROJECT_NAME}
)

ament_package()

