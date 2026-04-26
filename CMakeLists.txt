cmake_minimum_required(VERSION 4.1)
project(project_pppi)

set(CMAKE_CXX_STANDARD 20)

add_executable(project_pppi main.cpp
        calculator.h
        calculator.cpp)
