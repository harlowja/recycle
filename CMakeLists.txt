cmake_minimum_required (VERSION 3.10)
project(recycle)

add_library(recycle INTERFACE)
add_library(steinwurf::recycle ALIAS recycle)

target_compile_features(recycle INTERFACE cxx_std_14)

target_include_directories(recycle INTERFACE src/)
