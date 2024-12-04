cmake_minimum_required(VERSION 3.10)
project(SimpleCMakeProject)

# specify C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# add src directory
add_subdirectory(src)

# add test directory
enable_testing()
add_subdirectory(test)