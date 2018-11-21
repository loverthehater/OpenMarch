project(OpenMarch LANGUAGES CXX)

cmake_minimum_required(VERSION 3.10.0)

set(proj_src_files main.cpp)

add_executable(${PROJECT_NAME} ${proj_src_files})