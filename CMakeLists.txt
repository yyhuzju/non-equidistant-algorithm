cmake_minimum_required(VERSION 3.19)
project(PathPlanning)

set(CMAKE_CXX_STANDARD 14)
add_subdirectory(polyscope)
add_subdirectory(geometry-central)
add_subdirectory(DGtal)
add_executable(PathPlanning main.cpp)
target_link_libraries(PathPlanning PUBLIC polyscope geometry-central DGtal)
