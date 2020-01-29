cmake_minimum_required(VERSION 3.14)
project(ToDo)

set(CMAKE_CXX_STANDARD 17)

add_executable(ToDo src/main.cpp src/Lista.cpp include/Lista.h)