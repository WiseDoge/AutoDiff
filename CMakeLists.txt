cmake_minimum_required(VERSION 3.5)
project(AutoDiff)

set(CMAKE_CXX_STANDARD 11)

include_directories(include)

set(DEMO_FILES demo.cpp)

add_executable(Demo ${DEMO_FILES})