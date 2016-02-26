cmake_minimum_required(VERSION 3.0)
project(multithreading)
 
# Bring the headers
include_directories(include)
 
# Can manually add the sources using the set command as follows:
set(SOURCES
    src/main.cpp)
 
add_executable(multithreading ${SOURCES})