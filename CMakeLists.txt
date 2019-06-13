cmake_minimum_required(VERSION 3.10)
project(matrix_multi_threads)

set(CMAKE_CXX_STANDARD 11)
SET(CMAKE_CXX_FLAGS -pthread)


add_executable(matrix_multi_threads main.cpp)