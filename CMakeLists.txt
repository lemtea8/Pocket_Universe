cmake_minimum_required(VERSION 3.16)
project(PocketUniverse)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_subdirectory(SFML)

add_executable(PocketUniverse main.cpp)

target_link_libraries(PocketUniverse
    sfml-graphics
    sfml-window
    sfml-system
)
