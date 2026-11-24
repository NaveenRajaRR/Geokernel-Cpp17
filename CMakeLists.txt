cmake_minimum_required(VERSION 3.20)
project(geokernel_cpp17 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(geokernel_lab geokernel_lab.cpp)
target_compile_options(geokernel_lab PRIVATE -Wall -Wextra)