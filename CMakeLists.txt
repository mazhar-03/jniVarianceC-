cmake_minimum_required(VERSION 3.27)
project(untitled)

set(CMAKE_CXX_STANDARD 20)

set(JAVA_HOME "C:\\Program Files\\Java\\jdk-20")
include_directories(${JAVA_HOME}/include)
include_directories(${JAVA_HOME}/include/win32)

add_library(untitled SHARED library.cpp)


