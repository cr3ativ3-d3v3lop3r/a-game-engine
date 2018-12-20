cmake_minimum_required(VERSION 3.13)
project(a_game_engine)

set(CMAKE_CXX_STANDARD 17)

add_executable(a_game_engine main.cpp headers/Window.h src/Window.cpp)