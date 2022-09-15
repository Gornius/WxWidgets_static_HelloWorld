cmake_minimum_required(VERSION 3.10)
project(HelloWorldGUI)

set(wxBUILD_SHARED OFF)

add_subdirectory(wxWidgets)
add_executable(HelloWorldGUI main.cpp)
target_link_libraries(HelloWorldGUI wx::core wx::base)
