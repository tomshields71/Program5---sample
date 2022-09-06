cmake_minimum_required(VERSION 3.20)
project(Program5___sample)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Program5___sample
        ArrayStack.h
        stack_driver.cpp
        StackInterface.h)
