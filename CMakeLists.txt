cmake_minimum_required(VERSION 4.0)
project(sols)

set(CMAKE_CXX_STANDARD 26)

add_library(sols STATIC Sols.cpp Sols.h)

install(FILES Sols.h DESTINATION include)
install(TARGETS sols DESTINATION lib)
