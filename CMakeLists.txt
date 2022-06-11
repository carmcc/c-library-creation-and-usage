cmake_minimum_required(VERSION 3.22)
project(c_library_creation_and_usage C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(c_library_creation_and_usage
        main.c
        op.h)
