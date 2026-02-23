cmake_minimum_required(VERSION 3.20)

project(BehaviorTreeStarterKit LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(BehaviorTreeStarterKit
    BehaviorTree.cpp
    BehaviorTreeEvent.cpp
    BehaviorTreeOptimized.cpp
    BehaviorTreeShared.cpp
    Test.cpp
)

target_include_directories(BehaviorTreeStarterKit PRIVATE
    ${CMAKE_CURRENT_SOURCE_DIR}
)
