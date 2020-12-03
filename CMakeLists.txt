cmake_minimum_required(VERSION 3.16)

project(aoc)

add_executable(1 src/main1.cpp)
add_executable(2 src/main2.cpp)
add_executable(2_2 src/main2_2.cpp)

set_target_properties(1 2_2 3 PROPERTIES
  CXX_STANDARD 20)
