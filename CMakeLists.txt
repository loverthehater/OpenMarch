cmake_minimum_required(VERSION 3.10.0)
project(OpenMarch)

set(CMAKE_MODULE_PATH "${PROJECT_SOURCE_DIR}/cmake" ${CMAKE_MODULE_PATH})

find_package(Qt5Widgets REQUIRED)
list(APPEND QT_LIBRARIES ${Qt5Widgets_LIBRARIES})
list(APPEND QT_INCLUDES ${Qt5Widgets_INCLUDE_DIRS})
add_definitions(${Qt5Widgets_DEFINITIONS})
include_directories(${QT_INCLUDES})
add_executable(OpenMarch openmarch/main.cpp)
