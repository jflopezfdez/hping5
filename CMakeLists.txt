# Hping5 Top-Level CMake Configuration File.
cmake_minimum_required(VERSION 3.29)
project(hping5
  VERSION 1.0.0.0
  DESCRIPTION "C++20 re-write of the classic hping3 utility by antirez."
  HOMEPAGE_URL "https://github.com/jflopezfdez/hping5"
  LANGUAGES
    CXX
    C
)

# Specify the C++ Standard we want to run against and make sure it's mandatory
# across the entire project for consistency.
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED true)

# TODO: jflopezfernandez - Add project subdirectories.

