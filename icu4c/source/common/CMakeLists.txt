add_definitions(-DU_COMMON_IMPLEMENTATION) # required by common components
file(GLOB SRC_FILES *.h *.c *.cpp)
set(COMMON_SRC ${SRC_FILES} PARENT_SCOPE)
