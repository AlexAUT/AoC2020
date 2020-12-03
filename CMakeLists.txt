cmake_minimum_required(VERSION 3.16)

project(aoc)

add_executable(1 src/main1.cpp)
add_executable(2 src/main2.cpp)
add_executable(3 src/main3.cpp)

set_target_properties(1 2 3 PROPERTIES
  CXX_STANDARD 20)
