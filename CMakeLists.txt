cmake_minimum_required(VERSION 3.20)
set(CMAKE_CXX_STANDARD 17)

project(main)

add_subdirectory(pybind11)
pybind11_add_module(main main.cpp)
