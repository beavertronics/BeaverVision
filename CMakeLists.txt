cmake_minimum_required(VERSION 3.5.0)
project(BeaverVision VERSION 0.1.0 LANGUAGES C CXX)

add_executable(BeaverVision ${PROJECT_SOURCE_DIR}/src/test.cpp)

include(CTest)
enable_testing()

