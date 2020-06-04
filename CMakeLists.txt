cmake_minimum_required(VERSION 3.16)
project(C_Primer)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(.idea)

add_executable(C_Primer
        .idea/workspace.xml
        .gitignore
        README.md Charper02/HelloWorld.cpp Charper02/HelloWorld.h)
