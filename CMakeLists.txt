# Minimum CMakeLists.txt for DXRMV project
cmake_minimum_required(VERSION 3.10)
project(DXRMV)

# Set C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add executable for homework1
add_executable(homework1 homework1.cpp)
