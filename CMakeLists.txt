cmake_minimum_required(VERSION 3.10)

project(Yggdrasil LANGUAGES CXX)

# minimum required C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(Yggdrasil
    ../src/main.cpp
    # other .cpp files
)