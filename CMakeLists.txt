cmake_minimum_required(VERSION 3.6)
project(compilers_proj1_cs160)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(compilers_proj1_cs160 ${SOURCE_FILES})