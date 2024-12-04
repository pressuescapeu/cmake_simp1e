# add testing executable
add_executable(test_math test_math.cpp)

# link library to test
target_link_libraries(test_math math_lib)

# enable CTest
add_test(NAME MathTest COMMAND test_math)