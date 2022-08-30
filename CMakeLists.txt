# CMakeList.txt : CMake project for EndpointScanner, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("EndpointScanner")

# Add source to this project's executable.
add_executable (EndpointScanner "EndpointScanner.cpp" "EndpointScanner.h")

# TODO: Add tests and install targets if needed.
