project(cpp1Features)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_subdirectory (move)
add_subdirectory (rvalue_reference)
add_subdirectory (move_constructor)