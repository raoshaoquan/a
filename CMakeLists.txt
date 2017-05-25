cmake_minimum_required(VERSION 3.7)
project(a)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -fPIC")
set(SOURCE_FILES libraryA.cpp libraryA.h)
add_library(a ${SOURCE_FILES})