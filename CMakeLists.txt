cmake_minimum_required(VERSION 3.10)

project(ai_bird_feeder LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(ai_bird_feeder
    src/main.cpp
)
