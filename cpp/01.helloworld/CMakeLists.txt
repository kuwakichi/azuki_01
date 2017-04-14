cmake_minimum_required(VERSION 2.8)
PROJECT(HelloWorld)
include_directories ("${PROJECT_SOURCE_DIR}/${sub}")
add_executable(HelloWorld helloworld.cc)