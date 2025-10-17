cmake_minimum_required(VERSION 3.10)
project(SuffixArray)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(
    SuffixArray 
    src/main.cpp 
    src/SuffixArray.cpp
)

target_include_directories(SuffixArray PRIVATE include)