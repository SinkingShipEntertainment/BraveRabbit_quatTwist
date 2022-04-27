cmake_minimum_required(VERSION 3.1)
project(quatTwist)

set(CMAKE_MODULE_PATH ${CMAKE_CURRENT_SOURCE_DIR}/cmake)

add_subdirectory(source)

install(DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR}/modules/quatTwist/icons DESTINATION ./quatTwist)
install(DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR}/modules/quatTwist/scripts DESTINATION ./quatTwist)
install(FILES ${CMAKE_CURRENT_SOURCE_DIR}/quatTwist.mod DESTINATION .)
