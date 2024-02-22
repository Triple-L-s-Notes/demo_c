cmake_minimum_required(VERSION 3.27)
project(demo_c C)

set(CMAKE_C_STANDARD 11)

include_directories(include)

add_executable(demo_c
        include/utils.h
        src/main.c
        src/utils.c)
