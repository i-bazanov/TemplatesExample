cmake_minimum_required(VERSION 3.0)

project(MTC_test_task_templates)

add_executable(${PROJECT_NAME} main.cpp)
set_property(DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR} PROPERTY VS_STARTUP_PROJECT MTC_test_task_templates)
