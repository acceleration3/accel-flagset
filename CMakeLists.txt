cmake_minimum_required(VERSION 3.10)

project(accel-flagset CXX)

set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_STANDARD 20)

add_library(accel-flagset INTERFACE)
target_include_directories(accel-flagset INTERFACE "include/")