cmake_minimum_required(VERSION 3.3)
project(DoubleLinkedList)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(DoubleLinkedList ${SOURCE_FILES} BidiLinkedList.h BidiLinkedList.hpp)