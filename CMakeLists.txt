##
## Author: Sebastien Maire
## Contribs:
##

cmake_minimum_required(VERSION 2.8)
project(ECSess_GameEngine)

set(
    GameEngineSrcs
    src/tmp.cpp
)

add_library(${CMAKE_PROJECT_NAME}_GameEngine STATIC ${GameEngineSrcs})
target_link_libraries(${CMAKE_PROJECT_NAME}_GameEngine core_static)
add_dependencies(${CMAKE_PROJECT_NAME}_GameEngine core_static)
