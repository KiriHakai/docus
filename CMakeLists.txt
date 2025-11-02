cmake_minimum_required(VERSION 3.10)
project(docus)

set(CMAKE_CXX_STANDARD 14)

add_executable(compiled-app)

target_sources(compiled-app PRIVATE main.cpp)