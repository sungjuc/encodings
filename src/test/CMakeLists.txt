add_executable(benchmark_test
  benchmark_test.cc)

add_executable(performance_test
  performance_test.cc)

add_executable(edge_encoding_test
  edge_encoding_test.cc)

add_executable(delta_compression_test
  delta_compression_test.cc)

target_link_libraries(performance_test
utils)

target_link_libraries(edge_encoding_test
utils)

target_link_libraries(delta_compression_test
utils)