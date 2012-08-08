cmake_minimum_required(VERSION 2.8)
project(PROTO_LINK)

SET(CMAKE_MODULE_PATH ${PROJECT_SOURCE_DIR}/cmake-modules)

find_package(ZeroCIce)

set(CMAKE_CXX_FLAGS "-g -Wall")
add_subdirectory(examples)
