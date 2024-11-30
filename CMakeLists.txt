cmake_minimum_required(VERSION 3.28.0)
project(_m_test_ VERSION 0.1.0 LANGUAGES C CXX)


add_executable(_m_test_ M21/TASK_01.cpp)

include(CTest)
enable_testing()

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
