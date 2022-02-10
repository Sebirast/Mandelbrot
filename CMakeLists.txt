cmake_minimum_required(VERSION 3.22)

project("Mandelbrot")

set(CMAKE_CPP_RELEASE_FLAGS -O3 -march=native)

add_executable(${PROJECT_NAME} Main.cpp)