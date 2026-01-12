cmake_minimum_required(VERSION 3.10)
project(DSALearning)

set(CMAKE_CXX_STANDARD 17)

# Tell CMake where to look for .hpp files
include_directories(include)

# Create an executable for the Linked List test
add_executable(test_ll tests/data_structures/test_linkedlist.cpp)

# Create an executable for the Merge Sort test
add_executable(test_merge tests/algorithms/test_sorting.cpp)