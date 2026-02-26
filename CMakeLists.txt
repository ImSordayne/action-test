cmake_minimum_required(VERSION 3.17)
project(HelloWorld)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED OFF)

add_executable(HelloWorld src/HelloWorld.cpp)