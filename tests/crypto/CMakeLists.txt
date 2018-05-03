add_executable( test_compress compress.cpp )
target_link_libraries( test_compress fc )

add_test(NAME test_compress COMMAND fc/tests/crypto/test_compress WORKING_DIRECTORY ${CMAKE_BINARY_DIR})
