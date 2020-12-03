cmake_minimum_required(VERSION 3.16)

project(aoc)

add_executable(1 src/main1.cpp)

set_target_properties(1 PROPERTIES
  CXX_STANDARD 20)
