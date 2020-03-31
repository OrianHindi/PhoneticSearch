cmake_minimum_required(VERSION 3.15)
project(PhoeneticSearch)

set(CMAKE_CXX_STANDARD 14)

add_executable(PhoeneticSearch Test.cpp PhoneticFinder.cpp PhoneticFinder.hpp TestCounter.cpp )