cmake_minimum_required(VERSION 4.0)
project(sols C)

set(CMAKE_C_STANDARD 23)

add_library(sols STATIC sols.c sols.h)
