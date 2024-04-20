cmake_minimum_required(VERSION 3.25)
project(
    Playground
    VERSION 1.0
    LANGUAGES CXX
)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(Playground main.cpp)

message(STATUS "Used compiler: ${CMAKE_CXX_COMPILER} version ${CMAKE_CXX_COMPILER_VERSION}")
message(STATUS "Compiler flags: ${CMAKE_CXX_FLAGS}")
