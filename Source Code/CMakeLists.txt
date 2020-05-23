cmake_minimum_required(VERSION 3.14)
project(Source_Code)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Source_Code
        00082217.cpp
        assembly.h
        classes.h
        display_tools.h
        example.dat
        math_tools.h
        sel.h
        tools.h)
