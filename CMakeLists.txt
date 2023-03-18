cmake_minimum_required(VERSION 3.7.0)

project(helloworld)

include_directories(include)

aux_source_directory(src SRC)

add_executable(helloworld main.cpp ${SRC})