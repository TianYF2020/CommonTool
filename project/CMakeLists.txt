cmake_minimum_required(VERSION 3.12)

project(demo)

set(CMAKE_CXX_STANDARD 20)
# SET(CMAKE_C_COMPILER   /home/fhc/linux_driver/gcc-3.4.5-glibc-2.3.6/bin/arm-linux-gcc)
# SET(CMAKE_CXX_COMPILER /home/fhc/linux_driver/gcc-3.4.5-glibc-2.3.6/bin/arm-linux-g++)

add_executable(${PROJECT_NAME} main.cpp)