# CMakeList.txt: проект CMake для SingleLinkedList; включите исходный код и определения,
# укажите здесь логику для конкретного проекта.
#
cmake_minimum_required (VERSION 3.8)

project (SingleLinkedList)
set(CMAKE_CXX_STANDARD 17)
file(GLOB SOURCES *.cpp *.h)
add_executable("${PROJECT_NAME}" "${SOURCES}")

