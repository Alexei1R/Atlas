

cmake_minimum_required(VERSION 3.0)
project(AtlasExecutable)

set(SOURCES
       
)



add_executable(AtlasExecutable ${SOURCES})

target_link_libraries(AtlasExecutable
        Atlas
)



target_include_directories(AtlasExecutable PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/)