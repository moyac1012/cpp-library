cmake_minimum_required(VERSION 3.26)
project(cpp_library C)

set(CMAKE_C_STANDARD 23)

add_library(cpp_library library.c
        include/cpp_library/example.h)
