cmake_minimum_required(VERSION 3.5)

project(advent-of-code-2024 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(advent-of-code-2024 main.cpp)

include(GNUInstallDirs)
install(TARGETS advent-of-code-2024
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR}
    RUNTIME DESTINATION ${CMAKE_INSTALL_BINDIR}
)
