cmake_minimum_required(VERSION 3.13)
project(cop3014_lab02)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES circlearea.cpp name.cpp stringchar.cpp)

add_executable(circlearea.exe circlearea.cpp)
add_executable(name.exe name.cpp)
add_executable(stringchar.exe stringchar.cpp)


