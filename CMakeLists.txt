cmake_minimum_required(VERSION 3.10)

# Project name
project(CLOX)

# Set C++ standard
set(CMAKE_CXX_STANDARD 17)

# Include directories for header files
include_directories(${PROJECT_SOURCE_DIR})

# Collect all source files automatically
file(GLOB SOURCES "${PROJECT_SOURCE_DIR}/*.c")

# Add executable
add_executable(clox ${SOURCES})
