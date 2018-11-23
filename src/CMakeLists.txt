cmake_minimum_required(VERSION 3.10.0)
project(OpenMarch)

set(src_files main.cpp)
add_compile_options(CMAKE_CXX_COMPILER /c/mingw/bin/g++.exe)

add_executable(${PROJECT_NAME} ${src_files})