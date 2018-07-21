set(headers headerfile.h)

set(sources src/new.cpp)

ROOT_STANDARD_LIBRARY_PACKAGE(HW
			      HEADERS ${headers}
			      SOURCES ${sources})
