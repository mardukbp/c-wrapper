cmake_minimum_required(VERSION 3.5)
project(c_wrapper)

#set(CMAKE_CXX_STANDARD 11)

add_library(myLib MyClass.cpp MyClass.h)
target_include_directories (myLib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})

#add_library(mylibCpp MyClass.cpp MyClass.h)
#target_include_directories (myLibCpp PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
