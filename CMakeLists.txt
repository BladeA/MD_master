cmake_minimum_required(VERSION 3.9)
project(MD_master)

set(CMAKE_CXX_STANDARD 11)

add_executable(MD_master
        MD-master/main.cpp
        MD-master/vectormath.cpp
        MD-master/vectormath.h)
