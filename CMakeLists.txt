cmake_minimum_required(VERSION 2.8)
project(PROTO_LINK)

#######
# Provides a set of useful cmake macroses for ice users
# Thanx 2: Pau Garcia i Quiles, <pgquiles@elpauer.org>
SET(ZeroCIce_FIND_QUIETLY TRUE)    # Disable script's output
SET(ZeroCIce_FIND_REQIRED TRUE)    # Really can't continue build steps without Ice :)
SET(CMAKE_MODULE_PATH ${PROJECT_SOURCE_DIR}/cmake-modules/ZeroCIce-find)
find_package(ZeroCIce)
#######


set(CMAKE_CXX_FLAGS "-g -Wall")
add_subdirectory(examples)
