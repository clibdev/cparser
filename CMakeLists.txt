cmake_minimum_required(VERSION 3.16)
project(cparser)

set(CMAKE_CXX_STANDARD 14)

set(CMAKE_C_FLAGS_RELEASE "${CMAKE_C_FLAGS_RELEASE} -s")
set(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} -s")

add_executable(cparser main.cpp)
