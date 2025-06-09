cmake_minimum_required(VERSION 3.10)
project({{cookiecutter.project_slug}}VERSION 0.1.0 DESCRIPTION "{{cookiecutter.project_description}}" LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

include_directories(include)

file(GLOB SOURCES "src/*.cpp")

add_executable({{cookiecutter.project_slug}} ${SOURCES})