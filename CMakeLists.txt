cmake_minimum_required(VERSION 3.2)
project(MySlowTranCapture)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES local_addresses.cc local_addresses.h my_slow_tran_capture.cc my_slow_tran_capture.h)
add_executable(MySlowTranCapture ${SOURCE_FILES})