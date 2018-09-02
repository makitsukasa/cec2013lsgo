PROJECT(cec2013 CXX)

SET(CECSRC
  F1.cpp
  F2.cpp
  F3.cpp
  F4.cpp
  F5.cpp
  F6.cpp
  F7.cpp
  F8.cpp
  F9.cpp
  F10.cpp
  F11.cpp
  F12.cpp
  F13.cpp
  F14.cpp
  F15.cpp
  Benchmarks.cpp
  eval_func.cpp
)

SET(SRC
  F1.cpp
  F2.cpp
  F3.cpp
  F4.cpp
  F5.cpp
  F6.cpp
  F7.cpp
  F8.cpp
  F9.cpp
  F10.cpp
  F11.cpp
  F12.cpp
  F13.cpp
  F14.cpp
  F15.cpp
  Benchmarks.cpp
  eval_func.cpp
)

ADD_LIBRARY(cec2013 SHARED ${CECSRC})
TARGET_LINK_LIBRARIES(cec2013)

set(CMAKE_CXX_FLAGS "-std=c++17 -pedantic")
