project(set10108-lab03)
cmake_minimum_required(VERSION 3.17)
set(CMAKE_CXX_STANDARD 17)
include_directories(../contrib)

add_executable(increment increment.cpp)
add_executable(increment-mutex increment-mutex.cpp)
add_executable(increment-guarded increment-guarded.cpp)
add_executable(condition-variable condition-variable.cpp)
add_executable(test-guarded guarded.cpp test-guarded.cpp)
add_executable(test-stack test-stack.cpp)
add_executable(increment-atomic increment-atomic.cpp)
add_executable(atomic-flag atomic-flag.cpp)
add_executable(find-max find-max.cpp)
add_executable(monte-carlo-future monte-carlo-future.cpp)
add_executable(mandelbrot mandelbrot.cpp)
