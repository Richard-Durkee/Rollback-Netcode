cmake_minimum_required(VERSION 3.28)
project(Rollback_Netcode)

set(CMAKE_CXX_STANDARD 23)

add_executable(Rollback_Netcode main.cpp
        abstractClientFactory.cpp
        abstractClientFactory.h
)
