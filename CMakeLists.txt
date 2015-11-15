cmake_minimum_required(VERSION 3.3)
project(pthreads)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    enzyme.c
    enzyme.h
    smp2_tests.c
    testrunner.c
    testrunner.h)

add_executable(pthreads ${SOURCE_FILES})