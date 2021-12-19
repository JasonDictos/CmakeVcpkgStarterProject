# Error if cmake isn't at least this version
cmake_minimum_required(VERSION 3.20.5 FATAL_ERROR)

project(Example DESCRIPTION "An example project" VERSION 1.0.0 LANGUAGES CXX)

# C++20 
set(CMAKE_CXX_STANDARD 20)

add_subdirectory(example)