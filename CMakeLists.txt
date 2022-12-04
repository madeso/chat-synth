# CMake project for the polyphonic software synthesizer

cmake_minimum_required(VERSION 3.10)
project(synthesizer)
# Set the C++ standard to C++17

set(CMAKE_CXX_STANDARD 17)
# Add the source files for the synthesizer

set(SOURCES
src/synthesizer.cc
)
# Add the executable for the synthesizer

add_executable(synthesizer ${SOURCES})
# Link the synthesizer with the required libraries

#target_link_libraries(synthesizer
#m
#)
#Install the synthesizer

install(TARGETS synthesizer DESTINATION bin)
# Include the source files and headers for the synthesizer

target_include_directories(synthesizer PRIVATE src)

