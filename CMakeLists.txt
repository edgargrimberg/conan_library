cmake_minimum_required(VERSION 3.15)
project(conan_library CXX)

add_library(${PROJECT_NAME} src/library.cpp)
