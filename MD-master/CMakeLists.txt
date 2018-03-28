cmake_minimum_required(VERSION 3.6)
project(MD)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp vectormath.cpp vectormath.h)
add_executable(MD ${SOURCE_FILES})