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

##target_link_libraries()
add_library(${CMAKE_PROJECT_NAME}_GameEngine STATIC ${GameEngineSrcs})