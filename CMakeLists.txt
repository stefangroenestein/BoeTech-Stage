cmake_minimum_required(VERSION 3.6)
project(BoeTech_Stage)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(BoeTech_Stage ${SOURCE_FILES})