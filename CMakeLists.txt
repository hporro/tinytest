cmake_minimum_required(VERSION 3.1)
project(tinytest VERSION 0.1 LANGUAGES CXX C)

add_library(tinytest INTERFACE)
target_include_directories(tinytest INTERFACE ${CMAKE_SOURCE_DIR})

add_subdirectory(example)
