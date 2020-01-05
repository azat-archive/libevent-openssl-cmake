project(libevent-openssl-cmake)
cmake_minimum_required(VERSION 3.12)

set(CMAKE_MODULE_PATH "${CMAKE_CURRENT_SOURCE_DIR}/cmake/Modules")

add_subdirectory(openssl-cmake)
add_subdirectory(libevent)
