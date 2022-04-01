cmake_minimum_required(VERSION 3.16)

set(CMAKE_CXX_STANDART 11)
set(CMAKE_CXX_STANDART_REQUIRED ON)

project(formatter)

add_library(formatter STATIC formatter.cpp)
