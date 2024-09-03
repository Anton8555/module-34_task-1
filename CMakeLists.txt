cmake_minimum_required(VERSION 3.8)
project("module-34_task-1")

set(CMAKE_CXX_STANDARD 14)

set(CMAKE_PREFIX_PATH "D:\\Qt\\Qt5.12.12\\5.12.12\\mingw73_64\\lib\\cmake")

find_package(Qt5 COMPONENTS
        Core
        Gui
        Widgets
        REQUIRED)

add_executable("module-34_task-1" main.cpp)
target_link_libraries("module-34_task-1"
        Qt5::Core
        Qt5::Gui
        Qt5::Widgets)
