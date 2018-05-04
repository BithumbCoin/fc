add_executable( test_compress compress.cpp )
set(pthread_library pthread)
target_link_libraries( test_compress fc ${pthread_library})
#add_test(NAME test_compress COMMAND tests/crypto/test_compress WORKING_DIRECTORY ${CMAKE_BINARY_DIR})
