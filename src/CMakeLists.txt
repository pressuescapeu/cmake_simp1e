# add math_lib library
add_library(math_lib math_lib.cpp)

# add the executable
add_executable(main_app main.cpp)

# link library to executable
target_link_libraries(main_app math_lib)