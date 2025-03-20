cmake_minimum_required(VERSION 3.22.1)
project(RandomImage LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)

find_package(PNG REQUIRED)
include_directories(${PNG_INCLUDE_DIRS})

add_executable(RandomImage src/main.cpp src/random_image.cpp)
target_link_libraries(RandomImage ${PNG_LIBRARIES})
