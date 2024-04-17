cmake_minimum_required(VERSION 3.28)

project(Fxxk_Nvidia)

set(CMAKE_CXX_STANDARD 11)

set(CMAKE_EXE_LINKER_FLAGS -static)

add_executable(Fxxk_Nvidia main.cpp rc.rc)
