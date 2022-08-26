cmake_minimum_required(VERSION 3.2)

project(test_fsm_compact)

aux_source_directory(. SRC)	

add_executable(out ${SRC}) 