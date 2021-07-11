cmake_minimum_required(VERSION {{version}})

project({{projectname}} VERSION 1.0.0)

set(CMAKE_CXX_STANDARD {{std}})

include_directories(./include)

set(HEADER_FILES ./include/header_sample.h)

add_executable({{projectname}} main.cpp source_sample.cpp)
