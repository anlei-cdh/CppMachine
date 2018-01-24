# cmake_minimum_required(VERSION <specify CMake version here>)
project(CppMachine)

set(CMAKE_CXX_STANDARD 11)

include_directories(eigen)
include_directories(boost_1_66_0)

add_executable(CppMachine DecisionTree.cpp)
