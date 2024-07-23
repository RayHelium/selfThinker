cmake_minimum_required(VERSION 3.15)
project(TEST)

include_directories(include)



set(SRC main.cpp ./src/lib.cpp)
aux_source_directory(. SRC)
add_executable(obj ${SRC})
# add_compile_options(-wall -std=c++11 -o2)