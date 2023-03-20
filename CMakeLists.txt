cmake_minimum_required(VERSION 3.4...3.18)
set(CMAKE_CXX_STANDARD 17)

project(hello_world)

add_subdirectory(pybind11)
pybind11_add_module(hello_world hello_world.cpp)
