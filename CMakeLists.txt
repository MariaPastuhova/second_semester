cmake_minimum_required(VERSION 3.10)

project(second_semester)

set(CMAKE_CXX_STANDART 11)
set(CMAKE_CXX_STANDART_REQUIRED True)

include_directories(src)

add_executable(second_semester src/main.cpp src/utils.cpp)
