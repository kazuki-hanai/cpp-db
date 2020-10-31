cmake_minimum_required(VERSION 3.10)

project(db_tuto VERSION 0.1)
add_subdirectory (src) 
add_subdirectory (test)
enable_testing ()
add_test (NAME DBTest COMMAND ${PROJECT_SOURCE_DIR}/test/dbtest)
