cmake_minimum_required(VERSION 3.5)
project(c_wrapper)

#set(CMAKE_C_STANDARD 99)
#set(CMAKE_CXX_STANDARD 11)

add_library(myLib MyClass.cpp MyClass.h MyWrapper.cpp MyWrapper.h)
target_include_directories (myLib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
