cmake_minimum_required(VERSION 3.20) 
project(MyProjectTest) 
add_subdirectory(D:/1/Catch2 Catch2-build) 
add_executable(MyProjectTest Test_code.cpp ) 
target_link_libraries(MyProjectTest PRIVATE Catch2::Catch2)