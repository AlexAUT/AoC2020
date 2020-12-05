cmake_minimum_required(VERSION 3.16)

project(aoc)

add_executable(1 src/main1.cpp)
add_executable(1_2 src/main1_2.cpp)
add_executable(2 src/main2.cpp)
add_executable(2_2 src/main2_2.cpp)
add_executable(3_1 src/main3_1.cpp)
add_executable(3_2 src/main3_2.cpp)

set_target_properties(1 1_2 2 2_2 3_1 3_2 PROPERTIES
  CXX_STANDARD 20)
