cmake_minimum_required(VERSION 2.8)
project(cmake_wrapper)

include(conanbuildinfo.cmake)
conan_basic_setup()

include_directories(${CMAKE_SOURCE_DIR}/source_subfolder)
add_subdirectory("source_subfolder")
