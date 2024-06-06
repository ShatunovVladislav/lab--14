cmake_minimum_required(VERSION 3.26)
project(lab_14 C)

set(CMAKE_C_STANDARD 11)

add_executable(lab_14 main.c
        librarys/struct_vector/vector/vector.c
        librarys/struct_vector/vector/vector.h
        librarys/struct_vector/void_vector/void_vector.c
        librarys/struct_vector/void_vector/void_vector.h)
