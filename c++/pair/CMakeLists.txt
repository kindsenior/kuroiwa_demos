project(pair)

cmake_minimum_required(VERSION 2.8)
# set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++0x -W -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -W -Wall")

add_executable(test-pair test-pair.cpp)
