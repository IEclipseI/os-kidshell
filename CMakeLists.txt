cmake_minimum_required(VERSION 3.13)
project(os_kidshell)

set(CMAKE_CXX_STANDARD 14)

set (CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -fsanitize=address,undefined")

add_executable(os_kidshell main.cpp)