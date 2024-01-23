cmake_minimum_required(VERSION 3.10)

project(particle_filter)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++17")
add_executable(particle_filter main.cpp)