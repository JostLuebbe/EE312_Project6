cmake_minimum_required(VERSION 3.6)
project(Project6)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp Project6.cpp MazeParams.h Recursion.h)
add_executable(Project6 ${SOURCE_FILES})