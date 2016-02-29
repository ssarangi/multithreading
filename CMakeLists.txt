cmake_minimum_required(VERSION 3.0)
project(multithreading)

if(CMAKE_COMPILER_IS_GNUCC)
  set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
endif()

# Bring the headers
include_directories(include)
 
# Can manually add the sources using the set command as follows:
set(SOURCES
    src/main.cpp)
 
add_executable(multithreading ${SOURCES})