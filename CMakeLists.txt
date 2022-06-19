cmake_minimum_required(VERSION 3.0.0)
project(roguelike VERSION 0.1.0)

add_executable(roguelike "src/main.cpp")
target_link_libraries(roguelike SDL2 SDL2)
