ADD_LIBRARY(
  cxx-exercises-stl-code

  sensor.h
  sensor-const.h
  sensor-const.cpp
  sensor-random.h
  sensor-random.cpp

  uniq.cpp
  filter.cpp
  sensor-repo.cpp

)

TARGET_INCLUDE_DIRECTORIES(
  cxx-exercises-stl-code

  PUBLIC
  .
)
