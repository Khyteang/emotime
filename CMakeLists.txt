cmake_minimum_required(VERSION 2.8)

project(emotime)

find_package(OpenCV REQUIRED)
include_directories(${OpenCV_INCLUDE_DIRS})

set(ASSETDIR "${emotime_SOURCE_DIR}/assets" )
set(HEADERDIR "${emotime_SOURCE_DIR}/include" )
set(SRCDIR "${emotime_SOURCE_DIR}/src" )

SET(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS}" )

add_subdirectory(src)


