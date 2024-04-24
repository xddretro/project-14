cmake_minimum_required(VERSION 3.27)
project(untitled2 C)

set(CMAKE_C_STANDARD 11)

add_executable(untitled2 main.c
        libs/data_structures/vector/vector.c
        libs/data_structures/vector/vector.h
        libs/data_structures/vector_void/vector_void.c
        libs/data_structures/vector_void/vector_void.h)