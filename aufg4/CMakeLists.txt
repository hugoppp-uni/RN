cmake_minimum_required(VERSION 3.16)
project(BFT_Protocol)

include_directories(lib/include)

add_subdirectory(bft_base)
add_subdirectory(bft_server)
add_subdirectory(bft_client)
