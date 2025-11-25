cmake_minimum_required(VERSION 3.30)
project(TSP)

set(CMAKE_CXX_STANDARD 14)

include_directories(include)

add_executable(TSP
    include/TSP.hpp
    include/tsp_setup.hpp
    src/TSP.cpp
    src/tsp_setup.cpp
    main.cpp)
