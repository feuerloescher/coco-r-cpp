# auc - The Aurum compiler
# Copyright (c) 2016  Max Mertens <max.mail@dameweb.de>
# Distributed under the GNU GPL v3. For full terms see the file LICENSE.

cmake_minimum_required(VERSION 2.8)
project(coco-r-cpp)

include_directories("${PROJECT_SOURCE_DIR}")

file(GLOB_RECURSE SOURCE_FILES
    "${PROJECT_SOURCE_DIR}/*.h"
    "${PROJECT_SOURCE_DIR}/*.cpp"
)

add_executable(coco-cpp ${SOURCE_FILES})
