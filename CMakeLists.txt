cmake_minimum_required(VERSION 3.24)
project(untitled)

set(CMAKE_CXX_STANDARD 17)

add_executable(untitled main.cpp InsertionSort/insertionSort.cpp BubbleSort/bubbleSort.cpp SelectionSort/selectionSort.cpp QuickSort/quickSort.cpp)
