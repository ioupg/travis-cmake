cmake_minimum_required (VERSION 2.6)
project (Main)

# The version number.
set (MAIN_VERSION 1)

# add the binary tree to the search path for include files
# so that we will find TutorialConfig.h
include_directories("${PROJECT_BINARY_DIR}")

add_executable(Main main.cpp)