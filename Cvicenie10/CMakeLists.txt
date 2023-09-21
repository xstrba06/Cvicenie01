# CMakeList.txt : CMake project for Cvicenie10, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (Cvicenie10 "Cvicenie10.cpp" "Cvicenie10.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET Cvicenie10 PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
