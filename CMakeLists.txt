cmake_minimum_required(VERSION 3.3)
project(NatureServer)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES httpd.c)
add_executable(NatureServer ${SOURCE_FILES})