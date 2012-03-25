project(cppre)
include_directories(${INCLUDE_DIRECTORIES} ${cppre_SOURCE_DIR})
add_library(cppre Matcher.cpp Pattern.cpp WCMatcher.cpp  WCPattern.cpp)
