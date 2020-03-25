cmake_minimum_required(VERSION 2.8.3)
project(standard_objects)

find_package(catkin REQUIRED)
catkin_package(
)


# Adds our models onto the path
catkin_add_env_hooks(${PROJECT_NAME} SHELLS sh DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR}/env-hooks)
