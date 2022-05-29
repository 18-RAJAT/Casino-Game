cmake_minimum_required(VERSION 3.22)
project(Casino_Game)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Casino_Game
        Casino_Game.cpp
        Casino_Game.h)
