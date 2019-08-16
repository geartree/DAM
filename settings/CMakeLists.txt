cmake_minimum_required (VERSION 3.5)

project(settings)

add_library(${PROJECT_NAME} INTERFACE)
install(DIRECTORY include/ DESTINATION include/)

