cmake_minimum_required(VERSION 3.0)
project(xbot_env VERSION 1.0.0)

list(APPEND CMAKE_MODULE_PATH "${CMAKE_CURRENT_SOURCE_DIR}/cmake")
include(cmake/GenerateDeb.cmake)

install(
  FILES
  setup.sh
  .catkin
  DESTINATION "${CMAKE_INSTALL_PREFIX}"
  )

