cmake_minimum_required(VERSION 3.30)
project(Trading_Engine)

set(CMAKE_CXX_STANDARD 20)

add_executable(Trading_Engine main.cpp
        Stock.cpp
        Stock.h
        Equity.cpp
        Equity.h)
