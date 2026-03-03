# CMakeList.txt : CMake project for LCEModPatcher, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (LCEModPatcher "LCEModPatcher.cpp" "LCEModPatcher.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET LCEModPatcher PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
