cmake_minimum_required(VERSION 3.8 FATAL_ERROR)
project(cudart LANGUAGES CXX CUDA)
enable_language(CUDA)
add_executable(cudart main.cu)


