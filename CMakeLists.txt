cmake_minimum_required(VERSION 3.25.0)
project(QAMDemodulation VERSION 1.1.0)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_library(QAMDemodulation QAM\ Demodulation.cpp)

target_include_directories(QAMDemodulation PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
