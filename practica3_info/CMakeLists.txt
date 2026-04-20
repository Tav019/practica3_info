cmake_minimum_required(VERSION 3.16)

project(practica3_info LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(practica3_info main.cpp)

include(GNUInstallDirs)
install(TARGETS practica3_info
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR}
    RUNTIME DESTINATION ${CMAKE_INSTALL_BINDIR}
)
