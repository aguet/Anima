cmake_minimum_required(VERSION 3.16)
project(Anima VERSION 0.1.0)

add_executable(Anima main.cpp)

target_compile_features(Anima PRIVATE cxx_std_20)

#target_link_libraries(Anima -static-libgcc -static-libstdc++)
