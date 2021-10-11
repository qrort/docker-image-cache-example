cmake_minimum_required(VERSION 3.20)
project(docker_image_cache_example)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(docker_image_cache_example
        main.cpp)
