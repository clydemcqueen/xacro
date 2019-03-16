cmake_minimum_required(VERSION 3.5)
project(xacro)

find_package(ament_cmake REQUIRED)

install(PROGRAMS xacro.py DESTINATION lib/${PROJECT_NAME})

ament_package()