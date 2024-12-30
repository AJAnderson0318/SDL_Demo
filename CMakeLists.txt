
#Set Minimum Required CMake version
cmake_minimum_required(VERSION 3.10)

# Project name and Language
project(SDL_Demo LANGUAGES CXX)

#Add an Executable Target
add_executable(MyExecutable main.cpp)

#Link SDL to file

target_link_libraries(MyExecutable SDL2main SDL2)
