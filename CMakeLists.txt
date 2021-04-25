cmake_minimum_required(VERSION 3.14)
project(psplusplus)
add_executable(psplusplus src/main.cpp)
target_compile_features(psplusplus PUBLIC cxx_std_20)
