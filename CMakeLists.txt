cmake_minimum_required(VERSION 3.10)
project(toyjson)

set(CMAKE_CXX_STANDARD 11)


add_library(toyjson toyjson.cpp)
add_executable(toyjson_test test.cpp)
target_link_libraries(toyjson_test toyjson)
