cmake_minimum_required(VERSION 3.19)
project(MultiDGenericSim)

set(CMAKE_CXX_STANDARD 98)

add_executable(MultiDGenericSim main.cpp Element.h Population.h FileParse.cpp FileParse.h Simulation.cpp Simulation.h)