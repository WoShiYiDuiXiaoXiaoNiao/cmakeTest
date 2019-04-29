cmake_minimum_required(VERSION 3.5)
PROJECT(HELLO)
message(STATUS "this is binary dir" ${PROJECT_BINARY_DIR})
message(STATUS "this is SOURCE dir" ${PROJECT_SOURCE_DIR})
ADD_EXECUTABLE(hello main.c)

