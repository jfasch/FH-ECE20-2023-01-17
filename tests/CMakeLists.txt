ADD_EXECUTABLE(
  cxx-exercises-stl--suite

  # initial-failure.cpp

  test-uniq.cpp
  test-filter-generic.cpp
  test-sensor_repository_insert.cpp
  test-sensor_repository_lookup_positive.cpp
  test-sensor_repository_lookup_negative.cpp
  test-sensor_repository_remove.cpp
  test-sensor_repository_size_const.cpp
  test-sensor_repository_insert_duplicate.cpp
  test-sensor_repository_remove_nonexisting.cpp
)

TARGET_LINK_LIBRARIES(
  cxx-exercises-stl--suite

  cxx-exercises-stl-code
  gtest_main 
)
