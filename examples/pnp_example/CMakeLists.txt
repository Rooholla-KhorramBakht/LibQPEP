cmake_minimum_required(VERSION 3.6)
project(LibQPEP)

find_package(LibQPEP REQUIRED)
find_package(Eigen3 REQUIRED)
find_package(OpenCV REQUIRED)

add_executable(LibQPEP-epe main.cpp)

